(1) Comparing ES5 And ES6
------------------------------
Learning Outcome Addressed
 1. Compare ES5 and ES6 syntax

JavaScript ES6 Introduces New Functionality

ES6 is the current, standardized version of JavaScript. It provides a great deal of functionality to JavaScript, allowing for more rapid development. You'll have a greater appreciation for ES6 when you compare it to the older, ES5 functionality. 

ES5 vs. ES6 Comparison Example :

In ES5, you could specify a variable with var. ES6 introduces two additional ways of specifying a variable: const and let. Below you can see an example of const: 

var x = 10;

// Here x is 10

{

  const x = 2;

  // Here x is 2

}

// Here x is 10
 

Unlike var, which has global scope unless it is wrapped in a function, const and let have block scope by default. Leveraging block scope gives you more control and will make your code more predictable in its behavior.

Instructions:

Review new ES6 features by reading this article and respond to the following:Links to an external site.
https://www.w3schools.com/js/js_es6.asp


Select one feature from the article and compare ES5 and ES6.
Describe the differences through the lens of syntax, development speed, or functionality.
Submission Instructions:

 

Word count: 50-200
You are encouraged to reply to your peers. What did you find interesting about the ES6 feature they chose?
-------------------------
(2) Building Blocks Of Destructuring

----------------------------------------
Learning Outcome Addressed
-----------------------

Identify the building blocks of destructuring

Destructuring Review

In JavaScript, destructuring allows you to unpack values from arrays and objects into distinct variables. Here, a student’s ID is extracted from the `student` object using destructuring.

const student = { 
  id: 183294,  
  firstName: "Peter", 
  lastName: "Parker", 
  age: 19 
} 
function getID({id}) { 
  return id; 
} 
console.log(getID(student)); 

>>183294 
The `rest` operator allows you to collect the remaining values into a single array called `rest`. Here, the first element in the array is extracted to a variable named first. The rest of the elements are extracted to a variable named rest.

let numbers = [1, 2, 3, 4, 5]; 
let [first, ...rest]; 
console.log(first); 
console.log(rest); 
>>1 
>>[2, 3, 4, 5] 
Instructions:

Given the functionality of destructuring and rest explained above, write a discussion post that responds to the following:

How are destructuring and rest features similar? How are they different?
Share an example from a past project where you could have used destructuring or the rest operator.
Submission Instructions:

 

Word count: 50-200
You are encouraged to reply to your peers. What did you think of the example they shared?
--------------------------
(3) Challenges Of Scope
------------------------------

Learning Outcome Addressed
--------------------------
Discuss the impact of global scope vs. block scope on coding projects
------------------------
Instructions:

In ES6, the variable declarations `let` and `const` are block-scoped by default. The declaration `var` is globally scoped unless it is wrapped inside a function. 

If you were working on a codebase with a team, there could be several disadvantages of using globally scoped variables. 

Respond to the following:

What kinds of problems could block-scoped variables prevent?
Describe a situation in which it would be appropriate to use a globally scoped variable.  
Submission Instructions:

 

Word count: 50-200
You are encouraged to reply to your peers. Did you learn anything new from their explanation?
------------------------------





