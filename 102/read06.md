CSS allows you to create rules that specify how the content of 
an element should appear. For example, you can specify that 
the background of the page is cream, all paragraphs should 
appear in gray using the Arial typeface, or that all level one 
headings should be in a blue, italic, Times typeface.

CSS rule 
contains two parts: a selector and a declaration.
  Selector 
<p
             
Declaration {font-family: Arial;}

Declarations are made up of two parts: the properties 
of the element that you want to change, and the values 
of those properties
------------------------------------------
css can be used inlin or inside or external.
Using External CSS u have to link it in head:
<link rel="stylesheet" herf="">

<link> The link element can be used 
in an HTML document to tell the 
browser where to find the CSS

rel:This specifies the relationship 
between the HTML page and 
the file it is linked to. The value 
should be stylesheet when 
linking to a CSS file

herf:This attribute specifies the type 
of document being linked to. The 
value should be text/css.
----------------------------------------------
chapter 11
-----------------------
color in css formed in 4 ways
1-RGB(red,green,blue)
2-color name:(brown,orange,yellow)
3-hex code:: #ee3e80;
4-Hue color: hsla(0,100%,100%,0.5);
---------------------------
example:to change the color of text we use color
h1{
color:red;
}==name
h2{
color:(005,200.001); **start from 0 to 250**
}
h3{
#ee3e80;
}
for background color we use 
background-color
example:
body{
background-color:blue; this will change the background of your page
you can change background for part of your page for example:
h1 {
background-color: green;
}
h1{ background-color: hsla(0,100%,100%,0.5);
}
