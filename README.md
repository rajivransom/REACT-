**DAY 1 :**
The handling of this is also different in arrow functions compared to regular functions.

In short, with arrow functions, there is no binding of this.

In regular functions the this keyword represents the object that called the function, which could be the window, the document, a button or whatever.

With arrow functions the this keyword always represents the object that defined the arrow function.

normal function : const x= function(){
   return xyz;}   
 arrow function : const y= (x,y)=> x+y;

the main difference between these two functions is the way how these function deals with the "this" keyword.

In normal function "this" represents the object that called the function like "document" "windows" etc
but in the arrow function this keyword represents the object that defined the function.

Arrow function is the feature of ES6  introduced in **2016**

this refers to the **current context**.

Inside browser the global element of this is the ** window object**.


