Spread And Rest Operators
---------------------------

Learning Outcome Addressed
-------------------------
Use spread and rest to manipulate arrays
------------------------------

Spread
----------------------
ES6 - Spread and Rest operators
The rest and spread operators (...) allow you to further simplify your code by using destructuring to automatically capture the rest of an array or object in a variable (rest operator), or by spreading out variables into an array or object (spread).

For example, using the spread operator to combine the following objects:

const obj1= { a:1, b:2 }
const obj2= { c:3, d:4 }
console.log({...obj1, ...obj2})
Will result in the following object:

{ a:1, b:2, c:3, d:4 } // This will be the output of using the spread operator to combine obj1 and obj2
Here's another example, this time using the rest operator. The following function adds two numbers together:

function add(x, y, ...parameters) {
  return x + y;
}
 
add(1, 2, 3, 4, 5) // returns 3
The add function returns 3, because in JavaScript you can call a function with as many arguments as you want. However, only the parameters a and b are used within the add function, meaning the parameters parameter is unused. So, even though the add function was called with multiple arguments, it only uses the first two parameters and return the sum of those numbers a + b = sum, 1 + 2 = 3.

Using the rest operator allows you to capture the rest of these arguments, 3, 4, 5, which allows the add function to make use of all the arguments you pass to it. You'll see this in action on step 2 of this activity.

In the first step of this activity, you will practice the spread operator.

To complete this task, you need to do the following:

Combine the two arrays terrestrials and aquatics into one single array called allAnimals using the spread operator.
Print the allAnimals array to the console.
Note: Make sure the variable names match the instructions. Otherwise, your task will fail.

-----------------------------------------
ES6 - Using the Rest Operator
-------------------------------------
Now, it's time to practice the rest operator. In this task, you need to do the following:

Create a function called sumAll that will return the sum of any number of arguments passed to it. For example:
If you make the following call sumAll(1,2), it should return 3 since 1 + 2 = 3.
If you make the following call sumAll(1,2,3), it should return 6 since 1 + 2 + 3 = 6.
This function should accept an n number of arguments and return the sum of all those numbers.
Hint: Use the rest operator.

