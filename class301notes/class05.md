# Reading: Putting it all together

## [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. **What is the single responsibility principle and how does it apply to components?**
   - The single responsibility principle states that a component should do one thing and do it well. In the context of React components, it means that each component should ideally have a single responsibility or purpose.

2. **What does it mean to build a ‘static’ version of your application?**
   - Building a 'static' version means creating the UI without interactivity or dynamic data. It serves as a visual representation without functional behavior.

3. **Once you have a static application, what do you need to add?**
   - After creating a static version, you need to add interactivity by identifying the minimal set of mutable state that your app needs.

4. **What are the three questions you can ask to determine if something is state?**

   -   - Is it passed in from a parent via props?
       - Does it remain unchanged over time?
       - Can you compute it based on any other state or props in your component?

5. **How can you identify where state needs to live?**
   - Determine which components render based on that state. Identify a common owner component (a single component above all components that need the state).

## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

6. **What is a “higher-order function”?**
   - A higher-order function is a function that takes one or more functions as arguments or returns a function as its result.

7. **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**
   - Line 2 is defining a function `greaterThan`, which takes a parameter `n` and returns a function that tests if a given value is greater than `n`.

8. **Explain how either map or reduce operates, with regards to higher-order functions.**
   - Both `map` and `reduce` are higher-order functions. `map` transforms each element of an array using a provided function, while `reduce` iterates through the array, accumulating the values based on a provided function.

## Things I want to know more about

I am eager to delve deeper into understanding the relationship between the package.json file and the other pages in my React project. Recently, I encountered an error that stemmed from an outdated package.json, and I am keen to comprehend the specific reasons behind this issue.

