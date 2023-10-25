# HTML, CSS, and JavaScript Basics

## HTML - Ordered and Unordered Lists

1. **When to use an unordered list:** Use an unordered list when you want to display a list of items where the order doesn't matter. This creates a bulleted list, e.g., a list of favorite fruits.

2. **Changing bullet style:** To change the bullet style of unordered list items, use CSS and the `list-style-type` property. For example:
   ```css
   ul {
     list-style-type: square; /* Change bullet style to square */
   }
   
3. **Ordered list vs. unordered list:** Use an ordered list when the order of items is important, and you want them to be numbered sequentially. Use an unordered list when the order doesn't matter, and you want a bulleted list. For instance, use an ordered list for a recipe's list of steps.

4. **Changing numbers on ordered list items:** You can change the numbering of ordered list items using CSS. Two ways are:
   a. Using the `list-style-type` property, e.g., `list-style-type: roman;` to change numbers to Roman numerals.
   b. Using the `start` attribute on the `<ol>` element, e.g., `<ol start="10">`, to set the starting number.

## CSS - The Box Model

1. **CSS properties of margin and padding:** In the story of "The Box Model," Margin (Marge) and Padding (Paddy) are two characters. Marge is the protective boundary that keeps elements apart, preventing collisions. Paddy is the inner buffer that provides space within an element, keeping content cozy and isolated. Together, they ensure proper spacing and cushioning in the world of boxes.

2. **Parts of an HTML element's box:** The box model consists of four parts:
   a. **Content:** The actual content like text or images.
   b. **Padding:** The space between content and the border, providing internal spacing.
   c. **Border:** Surrounds padding and content, defining the visible boundary.
   d. **Margin:** The space outside the border, separating the element from others.

## JavaScript - Arrays, Operators, Expressions, Conditionals, Loops

1. **Data types in an Array:** In JavaScript, you can store various data types inside an array, including numbers, strings, objects, functions, and even other arrays.

2. **Accessing values in an Array:** The people array is valid in JavaScript. To access values, use index notation, e.g., `people[0]` for the first sub-array or `people[1][2]` for a specific element within a sub-array.

3. **Shorthand operators in JavaScript:** Shorthand assignment operators include `+=`, `-=`, `*=`, `/=`, `++`, and `--`. They perform operations and assign results in a shorter form.

4. **Evaluating an expression:** In the expression `(a + c) + b`, it evaluates to the string '10falsetog'. `(a + c)` concatenates '10' and 'false', and then this concatenated string is combined with 'dog'.

5. **Conditional statements:** Use conditional statements in a JavaScript program for making decisions based on data. For example, in a weather app, different advice can be shown based on the temperature.

6. **Use of Loops:** Loops are valuable when you need to perform repetitive tasks, like processing a list of items. For example, displaying a list of emails in an email client efficiently using a loop.

## Things I want to know more about

- I want to know more about how are the  CSS calculated based off of the values.
