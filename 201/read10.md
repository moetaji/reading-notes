**JS Debugging**

**in this chapter**

- the console and dev tools
**tools built within** the browser to help you to hunt for errors

- common problems
common sources of errors and how to solve th

- handling errors 
how code can deal with errors **gracefully**

<h1>Order Of Execution</h1>

some task cannot complete until another statement of function has been run
 it helps to know how script processed the order in which statement are executed 

 --------------------------------------

 <h1>excution contexts</h1>

 - Global context is the code in the script but not used in funcion 
 there is one global context in any page

 - function context is the code run within the function each function has its own function

 - Global scoop it is the varibal we declear outside of functions it can be used any where 

 - funcion-level scoop is the variable declared insid the function it can be only used insid that function

 -------------------------------------------

 <h1>The Stack</h1>

 JavaScript processes one line of code at a time  when the code need another statment to executed it stack (wait) until it get the statment then it will back to the current task 
 
 -----------------------------------------
 **understanding errors**

 in Javascript is importent to have a set of statment in your code to handel error because if the errors not handeld  it will stop working and the user will not know why it stoped 

 -------------------------------------------

 <h1>Errors Objects</h1>

  the browsers have tools to help you to find and read  your mistakes every errors object creat will have the following properties:

  - Name :type of execution
  - message:Description
  - fille number:name of the javaScript file
  - line number: line number of errors
  
  ------------------------------------
there is Seven built-in errors:

 -  Error:Generic error - the other errors 
    are all based upon this error 
- SyntaxError:Syntax has not been followed

- ReferenceError:whene you Tried to   reference a variable that is 
not declared/within scope 
- TypeError:An unexpected data type that 
cannot be coerced
- Range Error:Numbers not in acceptable range
- URI Error:encodeURI ().decodeURI(),and 
similar methods used incorrectly
- EvalError:eval() function used incorrectly

--------------------------------------------


