<h1>  chapter 3 list</h>
<h2>ther is three type of list</h2>  

- order list   
- un order list
------------------------------------------
<h1> Order list</h1>

The order list is created with the < ol> element
every item in the list will be bettwen < li>
tag and closing < /li>
  ex: 
<ol>
<li>first</li>
<li>sec</li>
<li>third</li>

--------------------------
<h1>unorder list</h1>

<h2>the un order list creat with ul element each element placed in li tag close tag /li</h2> ex:
<ul>
<li>one</li>
<li>two</li>
<li>three</li>
</ul>

---------------------------------------
<h1>definition list</h1>
<h2>created with dl element used usually for series of temrms</h2>

<h2>dt contain the term being defined</h2>
<h2>dd used to contain the definion<h2>

----------------------------------------
<h1>nested list</h1>
Browsers display nested lists 
indented further than the parent 
list. In nested unordered lists, 
the browser will usually change 
the style of the bullet point too.

![nested list](https://s3.amazonaws.com/webucator-how-tos/419.png)

---------------------------------
<h1>chapter 13 boxes<h1>
<h2>CSs treat each element as if it is insid its own box</h2>

--------------------------------------
<h1> control the dimension of a box-size width ,height<h1>
<h2>The most popular ways to 
specify the size of a box are 
to use pixels, percentages, or 
ems. Traditionally, pixels have 
been the most popular method 
because they allow designers to 
accurately control their size<h2>

--------------------------------------
ex:  
div.box {
height: 300px;
width: 300px;}

---------------------------------------
<h1>Limitng width</h1>
<h2>min-width , max-width</h2>
Some page designs expand and 
shrink to fit the size of the user's 
screen. In such designs, the 
min-width property specifies 
the smallest size a box can be 
displayed at when the browser 
window is narrow, and the 
max-width property indicates 
the maximum width a box can 
stretch to when the browser 
window is wide.

---------------------------------------
<h1>Limting height</h1>
<h2>min-height , max-height</h2>
 same way that you might 
want to limit the width of a box 
on a page, you may also want 
to limit the height of it. This is 
achieved by using the min-height
and max-height properties.

-----------------------------
<h1>Overflowing</h1>
overflow property tells the 
browser what to do if the content 
contained within a box is larger 
than the box itself. It can have 
one of two values: hidden or scroll

 - hidden simply hides any extra content not fiting insid the box 
 - scroll this add scrollbar to the box to see what missng insid the box

 -------------------------------------------

<h1> Every box has three proprties border ,margin , padding </h1>

- border Every box has a border (even if 
it is not visible or is specified to 
be 0 pixels wide). The border 
separates the edge of one box 
from another
- Margins sit outside the edge 
of the border. You can set the 
width of a margin to create a 
gap between the borders of two 
adjacent boxes.

- Padding is the space between 
the border of a box and any 
content contained within it. 
Adding padding can increase the 
readability of its contents

--------------------------
<h1>border width</h1>

The border-width property 
is used to control the width 
of a border. The value of this 
property can be in pixels or using one of the following values:

- thin
- medium
- thick
--------------------------------------------

<h1>js book chapter 2</h1>

<h2>Arrays</h2>
<p>array is special varibale it can store a list of values  it looks like a contener store values  related to same kind of varibale like colors=['red','blue','green'] </p>

-------------------------------------------
<h1>if statment</h1>
<h2> it's a method to give a condion for code if it's true excute this code or else  excute this code </h2>
the way we write if statment with else is like this 
if(condtion){
    if it's true exute this code
}
else{
    excute this code
}

----------------------------------------

<h1>Switch statment</h1>
<h2>you give a statment a varible with cases after every case we must have break</h2>

-------------------------------------------
<h1>loops</h1>
<h2> what loops dose will it used to check if the condion return true it will run the code if it's not true it will keep check until the condoion return true there is three type of loops </h2>

- while we use while loop if we don't know when condion return false

- for we use for loop if we know how many time we need until our condition return true

- do while it will run the statment at least one time even if condition false
