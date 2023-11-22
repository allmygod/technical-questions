# Technical Questions

## 1. What is OOP?
OOP means: Object Oriented Programming.
It is programming paradigm that organizes software design around objects and classes which can contain both data and functions.

## 2. Difference between Polymorphism vs Inheritance
- Inheritance allows classes to inherit properties and behaviors from other classes.
- Polymorphism means providing single interface to entities of different types.

Inheritance establishes a parent-child relationship between classes and promotes code reuse and supports hierarchy.
Polymorphism allows objects of different classes to be treated as objects of a common superclass.
Inheritance and Polymorphism are closely related, as Polymorphism is achieved through Inheritance. and Inheritance sets the foundation for Polymorphism.

## 3. SOLID principle
- Single Responsibility: each class should have a single Responsibility.
- Open / Closed principle: Open for Extension, Close for Modification
- Liskov Substitution Principle: objects of a superclass should be able to be replaced with objects of its subclass without affecting the correctness of the program.
- Interface Segregation principle: Segregation means keeping things as separate.
Segregating large interfaces into smaller, more specific ones. so that consumers only need to depend on the interfaces that are relevant to them.
- Dependency Inversion: Classes should depend upon interfaces or abstract classes instead of concrete classes and functions.

## 4. Difference between Architecture & System Design
Architecture deals with the `macro-level` structure and principles guiding the design, whereas system design deals with the `micro level` details and implementation of individual system components.

## 5. Coding Standard
It is a set of guidelines and best practices that define how code should be written and formatted in a consistent manner.
It has `indentation & formatting`, `comments & documentation`, `error & exception handling`, `code reusability and modularity`, `testing and debugging`, `performance considerations`, `version control and collaboration`.
Coding standard should align with project or organization specific requirements.

## 6. Benefit and Drawback of Having test
Benefit is improved code quality, increased confidence and faster development, easier maintenance. Drawback is time and effort, maintenance overhead.

## 7. Class component lifecycle : Hooks useEffect
`useEffect(() => {}, [])` replaces the combination of `componentDidMount`, `componentWillUnmount`.

`useEffect(() => {})` runs after every render by default. it is equivalent to `componentDidMount`, `componentDidUpdate` and the cleanup part of `componentWillUnmount`.


## 8. Design Pattern, commonly used in React
- Component Based Pattern: React is concept of components. that promotes reusability and modularity.
- Higher Order Component Pattern: takes a component and returns an enhanced version of the component
- Context Pattern, helps to avoid props drilling
- Controlled vs Uncontrolled Component

## 9. Event driven programming
It is a programming paradigm in which the flow of a program is determined by events or user actions rather than being strictly sequential.
In event-driven programming, the program waits for and responds to events triggered by the user, the operating system or other software components.

## 10. What is React?
It is a open-source JavaScript library for building frontend.
React uses a in-memory/virtual representation of the actual DOM that allows it to efficiently update only the necessary parts of the UI when the data changes, resulting in better performance.
