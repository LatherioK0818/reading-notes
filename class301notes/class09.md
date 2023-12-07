# Functional Programming Concepts

## 1. What is functional programming?

Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions. It avoids changing state and mutable data, relying instead on the application of functions and immutable data structures.

## 2. What is a pure function and how do we know if something is a pure function?

A pure function is a function where the output is determined only by its input parameters, without observable side effects. To identify a pure function, you need to check if it consistently produces the same result for the same input and does not modify any external state.

## 3. What are the benefits of a pure function?

The benefits of pure functions include easier reasoning about code, improved testability, and better parallelization. They contribute to code that is more modular, maintainable, and less prone to bugs.

## 4. What is immutability?

Immutability is the concept of making data unchangeable or not allowing it to be modified after it has been created. In functional programming, immutability is favored because it helps prevent unintended side effects and makes programs more predictable.

## 5. What is Referential transparency?

Referential transparency is a property of functions in which the same input will always produce the same output and has no side effects. It allows for easier understanding and reasoning about code.

# Videos

## Node JS Tutorial for Beginners #6 - Modules and require()

## 6. What is a module?

In Node.js, a module is a reusable piece of code that encapsulates related functionality. It allows you to organize your code into separate files, making it modular and easier to manage.

## 7. What does the word ‘require’ do?

`require` is a keyword in Node.js used to import and include external modules into your current JavaScript file. It enables you to use functions, variables, or objects defined in other modules.

## 8. How do we bring another module into the file that we are working in?

You bring another module into the file you are working in by using the `require` keyword, followed by the path to the module. For example:

```javascript
const myModule = require('./myModule');


# Things I want to know more about

## Functional Programming
- Explore advanced concepts in functional programming beyond the basics.
- How does functional programming compare to other programming paradigms?

## Node.js Modules
- Delve deeper into Node.js modules, understanding different module patterns.
- Learn about best practices for structuring large Node.js applications.
