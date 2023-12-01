# Readings: Passing Functions as Props

## React Docs - lists and keys

### .map() Method
1. **What does .map() return?**

   - The `.map()` method returns a new array with the results of calling a provided function on every element in the array.

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**
   - You can use the `.map()` method to loop through the array and render each value in JSX.

3. **Each list item needs a unique ____.**
   - Each list item needs a unique `key`.

4. **What is the purpose of a key?**
   - The purpose of a key is to help React identify which items have changed, are added, or are removed. It's crucial for efficient updates of the user interface.

### The Spread Operator

5. **What is the spread operator?**
   - The spread operator (`...`) is a syntax for expanding elements of an iterable (e.g., an array or object) into places where multiple elements are expected.

6. **List 4 things that the spread operator can do.**
   - a. Copying an array
   - b. Concatenating arrays
   - c. Adding elements to an array
   - d. Combining objects

7. **Give an example of using the spread operator to combine two arrays.**
   - Example: `const combinedArray = [...array1, ...array2];`

8. **Give an example of using the spread operator to add a new item to an array.**
   - Example: `const newArray = [...oldArray, newItem];`

9. **Give an example of using the spread operator to combine two objects into one.**
   - Example: `const combinedObject = {...object1, ...object2};`

## Videos: How to Pass Functions Between Components

10. **In the video, what is the first step that the developer does to pass functions between components?**
    - The developer defines a function in the parent component.

11. **In your own words, what does the increment function do?**
    - The increment function likely increases a numerical value or performs some operation when invoked.

12. **How can you pass a method from a parent component into a child component?**
    - You can pass a method from a parent component to a child component by passing it as a prop to the child.

13. **How does the child component invoke a method that was passed to it from a parent component?**
    - The child component can invoke the passed method by calling it as a function, using the prop received from the parent.

## References:
- [React Docs - Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
- [MDN Web Docs - Spread syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

## Things I want to know more about
- Further details on advanced use cases of the spread operator.
- In-depth examples of passing and handling functions between React components.
