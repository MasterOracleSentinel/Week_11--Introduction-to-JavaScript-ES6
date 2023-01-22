ES6 Word Count Assignment 
--------------------------
Learning Outcome Addressed
---------------------
Use ES6 key features
-----------------------
In this assignment, you’ll use ES6 syntax to convert a block of text into an array of words and calculate the frequency of each word. This will help you practice several key steps of the word count exercise Dr. Williams presented, although you will not be displaying those words on a page here.
-----------------------
ES6 Word Count
-----------------
ES6 Warmup - Word Count
In this activity, you will use a few popular ES6 features such as the arrow function, spread operator, and string manipulation.

Given a string of words, your task is to split this string into separate words stored in an array. Then, find the number of occurrences of each word and store that information in another array.

To complete this task, you need to do the following:

Using ES6 syntax, create an arrow function called words. This function takes a string as input and returns an array containing all the words in that string
The array of words should not contain any commas(,) or periods(.)
Using ES6 syntax, create an arrow function called wordFrequency. This function takes an array of words as input and returns an object where the key is the word and the value is the number of occurrences
Loop through each unique word and count the number of occurrences for that word in words
Assign that number to the object with the property being the current word in the loop
Here's an example of the expected output of the wordFrequency function:

{
    Duis: 2
    Excepteur: 2
    Lorem: 2
}
Note: Make sure the function names are an exact match to the instructions. If there's a mismatch, your task submission will fail.

Hint: One way to get a unique list of words is to use a JavaScript Set. Inside the wordFrequency function, use new Set(words) to remove all duplicates from the words array. Then use the spread operator to create a new array from that Set.


