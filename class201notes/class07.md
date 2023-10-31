# Domain Modeling

## Why We Need Domain Modeling

Domain modeling is essential for several reasons:

- **Understanding the Problem Domain:** It helps developers understand the real-world problem that the software is meant to solve.
- **Communication:** It provides a common language and understanding for the development team, stakeholders, and clients.
- **Structuring Code:** It helps in structuring code by defining the relationships and entities in the problem domain.
- **Reducing Ambiguity:** It reduces ambiguity, leading to more accurate and efficient software development.

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

# HTML Table Basics

## Tables for Page Layouts

Tables should not be used for page layouts because:

- **Semantic Meaning:** Tables are meant for tabular data, not layout. Using tables for layout purposes violates the semantic meaning of HTML elements.
- **Accessibility:** It can make websites less accessible to users with disabilities, as screen readers may not interpret layout tables correctly.
- **Responsiveness:** Tables don't adapt well to different screen sizes, making responsive design more challenging.

## Semantic HTML Elements in Tables

Three different semantic HTML elements used in an HTML `<table>` are:

- `<thead>`: This element defines the header section of a table and typically contains column labels or headings.
- `<tbody>`: It represents the main content of the table and contains the rows of data.
- `<tfoot>`: This element is used for the footer section of a table, typically containing summaries or totals.

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

# Introducing Constructors

## What is a Constructor and Its Advantages

A constructor in programming is a special method or function that is used for initializing objects in a class. Constructors have several advantages:

- **Object Creation:** Constructors create new instances of objects.
- **Initialization:** They initialize object properties with specific values.
- **Code Reusability:** They can be used to create multiple objects with the same properties and methods.
- **Customization:** Constructors allow you to set initial state or values based on parameters.

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

## "this" in Object Literal vs. Constructor

- In an object literal, "this" refers to the object itself. For example, if you have an object like `{ name: "John" }`, "this" inside a method of this object would refer to the object itself, which is `{ name: "John" }`.
- In a constructor, "this" refers to the instance of the object being created. When you create a new object using a constructor, "this" inside the constructor refers to that specific instance, allowing you to set properties for that instance.

## Object Prototypes Using A Constructor

[Object Prototypes](https://ui.dev/beginners-guide-to-javascript-prototype)

## Prototypes and Inheritance Analogy

**Question:** Explain prototypes and inheritance via an analogy from your previous work experience.

**Answer:** Prototypes and inheritance in JavaScript can be compared to a library and books analogy. Imagine a library with various categories of books, such as science, history, and fiction. Each category has a set of common properties, like title, author, and publication year.

- **Library (Prototype):** The library represents the prototype. It contains the common properties and functions shared among all categories of books.

- **Book Categories (Inherited Objects):** Each category of books (e.g., science, history) inherits from the library but can also

## Things I want to know more about

I don't have anything this moment.
