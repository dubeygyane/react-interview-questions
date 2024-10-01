# React Developer Interview Questions and Answers (2 Years of Experience)

This repository contains 25 common interview questions and answers for a React developer with 2 years of experience. The questions cover key concepts of React, including hooks, state management, performance optimization, and more.

## Table of Contents
1. [Key Features of React](#1-what-are-the-key-features-of-react)
2. [Functional vs Class Components](#2-explain-the-difference-between-functional-components-and-class-components)
3. [React Hooks](#3-what-are-react-hooks-and-why-are-they-used)
4. [Virtual DOM](#4-what-is-the-virtual-dom-and-how-does-react-use-it)
5. [State vs Props](#5-how-does-state-differ-from-props-in-react)
6. [useEffect](#6-what-is-the-purpose-of-useeffect-and-when-would-you-use-it)
7. [JSX](#7-what-is-jsx)
8. [React Refs](#8-what-are-react-refs-and-why-are-they-used)
9. [Key Prop](#9-what-is-the-key-prop-in-react-and-why-is-it-important)
10. [Higher-Order Components (HOC)](#10-explain-the-concept-of-higher-order-components-hoc-in-react)
11. [React Fragments](#11-what-are-react-fragments-and-how-are-they-used)
12. [Handling Forms in React](#12-how-do-you-handle-forms-in-react)
13. [Redux and React](#13-what-is-redux-and-how-does-it-work-with-react)
14. [useContext Hook](#14-explain-the-purpose-of-usecontext-and-when-you-would-use-it)
15. [Performance Optimization](#15-how-do-you-optimize-the-performance-of-a-react-application)
16. [Lazy Loading](#16-what-is-lazy-loading-in-react-and-how-is-it-implemented)
17. [useCallback vs useMemo](#17-what-is-the-difference-between-usecallback-and-usememo)
18. [Controlled vs Uncontrolled Components](#18-what-are-controlled-and-uncontrolled-components-in-react)
19. [Prop Drilling](#19-what-is-prop-drilling-and-how-do-you-avoid-it)
20. [React Router](#20-what-is-react-router-and-how-is-it-used)
21. [Lifting State Up](#21-explain-the-concept-of-lifting-state-up-in-react)
22. [Managing Side Effects](#22-how-would-you-manage-side-effects-in-a-functional-component)
23. [Controlled Components in Forms](#23-what-are-controlled-components-in-forms-and-why-are-they-recommended)
24. [Component Lifecycle in Functional Components](#24-how-do-you-handle-component-lifecycle-events-in-functional-components)
25. [Custom Hooks](#25-what-are-custom-hooks-and-how-do-you-create-one)

---

### 1. What are the key features of React?
React provides a component-based architecture, a virtual DOM for efficient rendering, and one-way data binding. It also supports reusable components and hooks for managing state and lifecycle events.

### 2. Explain the difference between functional components and class components.
Functional components are stateless and rely on hooks like `useState` for state management. Class components have lifecycle methods and manage their own state but are more verbose than functional components.

### 3. What are React hooks, and why are they used?
React hooks like `useState` and `useEffect` allow developers to manage state and side effects in functional components, eliminating the need for class components and simplifying code.

### 4. What is the virtual DOM, and how does React use it?
The virtual DOM is a lightweight, in-memory representation of the real DOM. React uses it to track changes and update the real DOM only where necessary, improving performance.

### 5. How does state differ from props in React?
State is managed within a component and can change over time, while props are passed from parent to child components and are immutable in the child.

### 6. What is the purpose of `useEffect`, and when would you use it?
`useEffect` is used to handle side effects in React functional components, such as fetching data or modifying the DOM after rendering.

### 7. What is JSX?
JSX stands for JavaScript XML, allowing developers to write HTML-like code within JavaScript. JSX is syntactic sugar for `React.createElement`.

### 8. What are React refs, and why are they used?
Refs are used to access and manipulate DOM elements or React components directly, commonly used for managing focus or animations.

### 9. What is the `key` prop in React, and why is it important?
The `key` prop uniquely identifies elements in a list. It helps React to efficiently update only the elements that change, avoiding unnecessary re-renders.

### 10. Explain the concept of higher-order components (HOC) in React.
HOCs are functions that take a component and return a new component with enhanced functionality, often used to reuse component logic.

### 11. What are React fragments, and how are they used?
React fragments (`<React.Fragment>` or `<>`) allow developers to group multiple elements without adding extra nodes to the DOM.

### 12. How do you handle forms in React?
Forms in React are typically handled using controlled components, where the form input is synchronized with the component's state.

### 13. What is Redux, and how does it work with React?
Redux is a state management library that provides a global store. In React, it allows components to connect to this store to manage the application state using actions and reducers.

### 14. Explain the purpose of `useContext` and when you would use it.
`useContext` is used to access data in a context without prop drilling, allowing easier state sharing across deeply nested components.

### 15. How do you optimize the performance of a React application?
Performance can be optimized by using memoization (`React.memo`, `useMemo`, `useCallback`), lazy loading components, and using proper `key` props in lists.

### 16. What is lazy loading in React, and how is it implemented?
Lazy loading loads components only when needed. It is implemented using `React.lazy` and `Suspense` for better performance and faster load times.

### 17. What is the difference between `useCallback` and `useMemo`?
`useCallback` is used to memoize functions, while `useMemo` is used to memoize the result of expensive computations, preventing unnecessary recalculations.

### 18. What are controlled and uncontrolled components in React?
Controlled components manage input form values through state, while uncontrolled components rely on the DOM to manage form data, typically accessed via refs.

### 19. What is prop drilling, and how do you avoid it?
Prop drilling refers to passing data through many layers of components. It can be avoided by using `useContext` or state management libraries like Redux.

### 20. What is React Router, and how is it used?
React Router is a library for managing navigation and routes in React applications. It allows developers to map URL paths to components.

### 21. Explain the concept of lifting state up in React.
Lifting state up means moving shared state to the closest common ancestor of components that need it, ensuring consistent data flow.

### 22. How would you manage side effects in a functional component?
Side effects are managed using the `useEffect` hook, where you can perform actions after the component renders, such as data fetching or DOM manipulation.

### 23. What are controlled components in forms, and why are they recommended?
Controlled components sync form input with the component's state, providing better control over form behavior, validation, and updates.

### 24. How do you handle component lifecycle events in functional components?
Lifecycle events in functional components are handled using the `useEffect` hook, which can mimic `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`.

### 25. What are custom hooks, and how do you create one?
Custom hooks are functions that encapsulate reusable logic using React hooks. You create one by writing a function that can use other hooks like `useState` and `useEffect`, then use it across components.

---

## License
This content is open source and available under the [MIT License](LICENSE).
