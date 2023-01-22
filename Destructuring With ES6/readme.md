Destructuring With ES6
------------------------

Learning Outcome Addressed
------------------------------
Use destructuring assignment syntax to unpack values from arrays and objects

-----------------------------------------------------

Using ES6 Features
-------------------------

ES6 - Destructuring
ES6 introduces ways to make your JavaScript code more simple. One of the way this is achieved is called destructuring.

Destructuring allows you to simplify your JavaScript code by breaking down complex structures into simpler and more manageable pieces. This is especially useful when dealing with complex arrays or objects.

Destructuring in action
Let's examine the following example to see how destructuring will make your code much simpler. The following code merges two objects without destructuring:

var obj1 = { a: 1, b: 2 } // declares an object that has 2 properties a and b
var obj2 = { a: 2, c: 3, d: 4} // declares an object that has 3 properties a, c and d
var obj3 = Object.assign(obj1, obj2) // merges the two objects declared
In this example, we had to use the Object.assign method to merge the two objects. This creates dependency on that function and doesn't looks very clean overall.

Luckily, we can achieve the same thing using destructuring in ES6 with the following code:

var obj1 = { a: 1, b: 2 } // declares an object that has 2 properties a and b
var obj2 = { a: 2, c: 3, d: 4} // declares an object that has 3 properties a, c and d
const obj3 = {...obj1, ...obj2} // merges the two objects declared
As you can see in this example, the code for merging two objects in ES6 is much cleaner and more simple.

Your Task
In this activity, you will practice destructuring by using it to manipulate arrays and objects in the given code.

Each section of code is defined using comments.

To complete this task you need to do the following:

In the "Array Destructuring" section, you need to destruct the array books into four separate variables: fiction, horror, literary and science. Then print all variables to the console.
In the "Object Destructuring" section, you need to destruct the object Student into three separate variables: firstName, university and studentid. Then print all variables to the console.
All variables should contain strings or numbers, not arrays.
All variable names should be respected. If your variable names do not match the instructions, your task will fail.
