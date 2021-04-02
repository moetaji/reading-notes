<h1>Literals Notation Object</h1>
<h2> this is the easiest way to creat object</h2>
<p>the object is the curly braces and thier contents.</p>
<h2>accessing an object and dot notation</h2>
<p>we can use dot to access a property or using sequar bracets</p>
the way to acssess property or method of an object is by the name of the object ,followed by a period,then the name of of the property or method.
</p>

----------------------------------------------

<h1>Document Object Model(DOM)</h1>
<p> how JavaScript can acces and updat an html page model while it is in the browsers window.
</p>

---------------------------------

<h1>DOM Tree</h1>
<p>browseres loads a web page the model of that page called DOM tree
</p>

-------------------------------------

<h1>access and updat DOM Tree</h1>

- locate the node that represent the element you want to work in

- use tex content,child element ,attributes.

--------------------------------------

<h2>acsses the element</h2>

<p> here is some commmon ways to slecet an element </p>

- getElemntByid()
<p> use the value of an element id attribute</p>

- querySelector()
<p> Css slector and returns the first matching element.</p>

- getElementbyClassName()
<p> slecet all element have the same class </p>

- getElementsByTagName('tagName)
<p> select all elements on the page with the tag name this method faster than queryselctor.</p>

---------------------------------------

<h1>Traversing the DOM</h1>
 
 <p> select another element in relation to it using five properties</p>

 - parentNod
 <p>finds the element node for the contatining element in html</p>

 - previousSibling,nextSilibing
 <p>these properties find the previous or the next silibing </p>

 - firstChild,lastCHild
<p> slect the first or the last CHild of the current element</p>

------------------------------------------

<h2>if u use (previousSibling,nextSilibing)
they don't have previous or next silibing the result will be Null</h2>

-----------------------------------
