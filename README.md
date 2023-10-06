# codedamn-problem-2

JavaScript Arrow Functions
Easy
984
140
58.1% Acceptance
Welcome to this practical arrow functions lab where you will explore and learn about JavaScript arrow functions, their creation, and how to export them.

Overview Arrow functions, introduced with ES6, are a new way to write JavaScript functions. They are excellent when working with functional programming styles. What makes them interesting is their brevity and the fact that they don't create their own this context.

Arrow Functions Notations

Expression Syntax: If your function takes a single parameter and returns a single expression, you can write it in its shortest form like (param) => expression

Multiline Syntax: If your function code is too extensive, you need brackets and a return statement:

(param1, param2) => {
  // Function body
  return result;
}
No Parameter: If your function doesn't have any parameters, you need to include an empty set of parentheses:

() => {
  // Function body
  return result;
}
This Binding In Arrow Functions Arrow functions do not have their own this value. The value of this inside an arrow function remains the same throughout the lifecycle of the function and is always bound to the value of this in the closest non-arrow parent function.

Arrow functions are a simplified syntax for writing function expressions in JavaScript, introduced with ES6. They are not just syntactically different; arrow functions come with an added advantage: they bound the this keyword to the surrounding (lexical) context.

Now that the lesson is complete, let's just create a simple Arrow Function

Steps
Declare a constant greet and assign an arrow function that takes name as a parameter.
Make the function return a string greeting, embedding name variable within it.
Finally, export your greet function with export default greet; to make it available for the tests.
This Lab uses ESM Imports, make sure to use default export instead of module.exports

That's it, you've completed all the tasks to pass this lab! Kudos 🎉

12345678
// Create the greet arrow function here and export it as default.
const greet =(name) => `Hello, ${name}!`
export default greet;
// Sample Tests for your greet function
console.log(greet("Neo"));
console.log(greet("Trinity"));
console.log(greet("Morpheus"));

