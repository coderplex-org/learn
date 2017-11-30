# <p align="center">ReactJS</p>

### Preface

An open source javaScript library for building user interfaces by Facebook inc.

### Why ReactJS ?

- **View in MVC** – ReactJS is the view layer in our applications and it does this job really well without trying to achieve anything more.

- **Virtual DOM** – This is probably why most developers are so attracted to React. React manages its own DOM in memory. The most expensive operation most web apps suffer is mutating the DOM. React's approach is to maintain a virtual representation of the DOM which allows it to calculate differences in the DOM so that it only mutates the part of the DOM that actually needs to be updated. This is a huge benefit!

- **Declarative** – Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes.

- **Component-Based** – Build encapsulated components that manage their own state, then compose them to make complex UIs.

- **Server Side Rendering** – Combining a NodeJS server and ReactJS helps us build even more complex applications by pre-rendering the initial state of our ReactJS components.

- **Javascript** – It is JavaScript after all. We can use latest JavaScript goodies by transpiling our code with the tools we prefer like webpack, browserify, rollup, babel etc

- **Non-Opinitated** – It doesnt make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code.

- **Testability** – React components simplify testing greatly. As a proof of it's simplicity, our new web client has more tests than any of our other clients.

- **Functional Programming** – ReactJS stateless components act like pure functions while composition is highly enforced instead of inheritance to reuse code between components.

# Curriculum
- [Prerequisites]()
- []

## Prerequities
Experience with the basic web technologies ie. HTML, CSS & JavaScript will help.

## Basics
- ["Hello, World!" with create-react-app](https://reactjs.org/docs/hello-world.html)
- [Components & Props](https://reactjs.org/docs/components-and-props.html)
- Popular ES6+ features using in React Apps
 –[Arrow Functions](http://babeljs.io/learn-es2015/#ecmascript-2015-features-arrows-and-lexical-this)
  - [Object Destructuring](http://babeljs.io/learn-es2015/#ecmascript-2015-features-destructuring)
  - [Classes](http://babeljs.io/learn-es2015/#ecmascript-2015-features-classes)
  - Static fields <!-- What does this mean? -->
- Communicating Between Components
  - Parent To Child using 'props'
  - Child To Parent using 'callbacks'
- [Understanding React's Component Lifecycle](https://medium.com/@baphemot/understanding-reactjs-component-life-cycle-823a640b3e8d)
- Component State & this.setState
- Stateless Functional Components
- Controlled & Uncontrolled Inputs
- Create a simple login form with React
- Accessing DOM Elements from React Components
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Handling Errors](https://reactjs.org/docs/error-boundaries.html)
Imperative vs Declarative
Composition
Unidirectional Dataflow
JSX
Virtual DOM
ES6 Classes
state
props
children
prop-types package
createElement
functional setState
Lifecycle Hooks
Container vs Presentational Components
Stateless Functional Components
Sytnthetic Events
Private Stateless Functional Components
Introduction to React

    React.js 
        What is it? 
        What problem does it solve? 
    Development Eco-System 
    React versus other frameworks

Key React components

    Editor and Web Server 
    Browser Development Tools 
    Components
    Virtual DOM
    Dataflow
    JSX

Your First React UI

    Understanding the components
    Building a Hello World Component 

JSX 

    What is JSX? 
    Using JSX 
    Using React with JSX 
    Using React without JSX 
    Precompiled JSX with Babel 

Working with Components 

    Component Life-Cycle 
    Properties and State 
    Virtual DOM 
    Events 
    Compositions 
    Reusable Components 

Forms 

    Controlled Components 
    Uncontrolled Components 
    Review of React

        What is it?
        Key React concepts and components
        Building a Hello World UI

    React and ES2015 

        ES2015 features which impact React 
        How to create components with ES2015 
        Using Babel for ES2015 and JSX 
        Using WebPack with React 
        Using Immutable.js 

    Advanced React Components 

        Component Life-Cycle 
        Virtual DOM 
        Events 
        State Machines 
        Compositions 
        Communication Between Components 
        Reusable Components 
        Cloning Components 

    Introduction to Flux 

        Key Flux concepts
        Actions
        Dispatchers
        Stores
        Flows

    Building your first Flux application

        Organizing your in code  and understanding the mental model
        Creating your Hello World
        Incorporating AJAX and Web Sockets 

    Working with Dispatchers 

        Understand the purpose, and design 
        Callbacks and the Dispatcher

    Stores 

        Understand the purpose of stores 
        Associating stores with the dispatcher

    Components 

        How to connect into stores 
            How to connect into actions 

    Redux 

        Explore differences between Redux and normal Flux 
        Reducer Functions 
        Working with one store 
        Advantages and Disadvantages of Redux 

    Working with the DOM 

        Referencing DOM Elements 
        DOM Manipulation 
        HTML 5 Drag and Drop 

    Node.js and Server DOM Manipulation 
    Unit Testing with TestUtils 

        Unit Testing with Mocha, Chai and Sinon 
        How to write React Component Unit Tests with Mocha and Chai 
        How to spy with Sinon 
        Testing Components 
        Testing DOM Manipulations 
        Testing Properties and State 
        Simulating Events 

### Intermediate
- CSS in JS
  - [styled-components](https://www.styled-components.com/)
  - [glamorous](https://blog.kentcdodds.com/introducing-glamorous-fb3c9f4ed20e)
- [React's Synthetic Event System](https://reactjs.org/docs/error-boundaries.html)
- [React Router](https://reacttraining.com/react-router/core/guides/philosophy)
- SSR

### Advanced
- Animations
- Redux (An entirely different topic altogether)
- Webpack (This might require a different roadmap altogether)
- [React Under The Hood](https://bogdan-lyashenko.github.io/Under-the-hood-ReactJS/)
