# Reading Component-Based Architecture

[Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
## 1. What is a "component"?

- A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exports it as a higher-level interface. This definition is aligned with the principles of component-based architecture.

## 2. What are the characteristics of a component?

- **Reusability:** Components are designed to be reused in different situations in various applications. Some may be designed for specific tasks.
- **Replaceable:** Components can be freely substituted with other similar components.
- **Not context-specific:** Components operate in different environments and contexts.
- **Extensible:** A component can be extended from existing components to provide new behavior.
- **Encapsulated:** Components depict interfaces, allowing the caller to use functionality without exposing internal processes or variables.
- **Independent:** Components are designed to have minimal dependencies on other components.

## 3. What are the advantages of using component-based architecture?

- **Ease of Deployment:** New versions can be easily replaced without impacting other components or the system.
- **Reduced Cost:** Use of third-party components spreads development and maintenance costs.
- **Ease of Development:** Components implement well-known interfaces, allowing development without impacting other system parts.
- **Reusable:** Components can be used across multiple applications or systems, spreading development and maintenance costs.
- **Modification of Technical Complexity:** Components modify complexity through the use of a component container and its services.
- **Reliability:** System reliability increases as individual component reliability enhances the overall system via reuse.
- **System Maintenance and Evolution:** Easy to change and update the implementation without affecting the rest of the system.
- **Independence:** Components allow independent development by different groups in parallel, enhancing productivity for current and future software development.

## React and Props:

[What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

## 1. What is "props" short for?

- "Props" is short for "properties."

## 2. How are props used in React?

- In React, props are used to pass data from one component to another. They are essentially parameters that a parent component passes down to its child components.

## 3. What is the flow of props?

- Props flow in a unidirectional manner, from parent to child components. Parent components pass data through props, and child components receive and use that data. This ensures a clear and predictable data flow within the React application.

## Things I want to know more about:

