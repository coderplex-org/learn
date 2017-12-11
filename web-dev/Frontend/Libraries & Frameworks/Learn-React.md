# ReactJS

# Curriculum

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Preface](#preface)
  * [Prerequities](#prerequities)
  * [Choosing ReactJS ?](#choosing-reactjs-)
  * [Philosophy](#philosophy)
* [Getting Started](#getting-started)
  * [Trying React](#trying-react)
  * [Create React App](#create-react-app)
  * [JavaScript XML Syntax](#javascript-xml-syntax)
* [Components](#components)
  * [Custom Components](#custom-components)
  * [Rendering](#rendering)
  * [Conditional Rendering](#conditional-rendering)
  * [Data flow](#data-flow)
  * [Lifecycle](#lifecycle)
  * [Events](#events)
* [Forms](#forms)
  * [Controlled Components](#controlled-components)
  * [Uncontrolled Components](#uncontrolled-components)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Preface

## Prerequities

Experience with the basic web technologies ie. HTML, CSS & JavaScript will help.

## Choosing ReactJS ?

React is an open source javaScript library for building user interfaces by Facebook inc.

* **View in MVC** – ReactJS is the view layer in our applications and it does this job really well without trying to achieve anything more.

* **Virtual DOM** – This is probably why most developers are so attracted to React. React manages its own DOM in memory. The most expensive operation most web apps suffer is mutating the DOM. React's approach is to maintain a virtual representation of the DOM which allows it to calculate differences in the DOM so that it only mutates the part of the DOM that actually needs to be updated. This is a huge benefit!

* **Declarative** – Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes.

* **Component-Based** – Build encapsulated components that manage their own state, then compose them to make complex UIs.

* **Server Side Rendering** – Combining a NodeJS server and ReactJS helps us build even more complex applications by pre-rendering the initial state of our ReactJS components.

* **Javascript** – It is JavaScript after all. We can use latest JavaScript goodies by transpiling our code with the tools we prefer like webpack, browserify, rollup, babel etc

* **Non-Opinitated** – It doesnt make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code.

* **Testability** – React components simplify testing greatly. As a proof of it's simplicity, our new web client has more tests than any of our other clients.

* **Functional Programming** – ReactJS stateless components act like pure functions while composition is highly enforced instead of inheritance to reuse code between components.

## Philosophy

### Resources

| Concept                   |                   Best Video Resource                    |                                     Best Text Resource                                     |                                Documentation                                 | Duration |
| :------------------------ | :------------------------------------------------------: | :----------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :------: |
| Best practices with react | [JSConf EU](https://www.youtube.com/watch?v=x7cQ3mrcKaY) | [Medium](https://medium.com/@nimelrian/thinking-in-react-a-paradox-statement-33c19e2eb9e2) | [ReactJS/thinking-in-react](https://reactjs.org/docs/thinking-in-react.html) | 1 hours  |

### Tasks :

* Add

# Getting Started

## Trying React

### Resources

| Concept          |                                Best Video Resource                                |                                Best Text Resource                                |                                    Documentation                                    | Duration |
| :--------------- | :-------------------------------------------------------------------------------: | :------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------: | :------: |
| Trying out React | [EggHead](https://egghead.io/lessons/react-write-hello-world-with-raw-react-apis) | [React Armory](http://jamesknelson.com/learn-raw-react-no-jsx-flux-es6-webpack/) | [ReactJS/installation](https://reactjs.org/docs/installation.html#trying-out-react) | 6 hours  |

### Tasks :

* Make a HTML file with ReactJS as script tag in the head.

- Make a simple km to miles converter in that one file.

## Create React App

### Resources

| Concept                      |                                     Best Video Resource                                      |                                        Best Text Resource                                        |                                         Documentation                                         | Duration |
| :--------------------------- | :------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------: | :------: |
| Create-React-App boilerplate | [EggHead](https://egghead.io/lessons/react-react-fundamentals-development-environment-setup) | [FacebookIncubator/cra](https://github.com/facebookincubator/create-react-app#create-react-app-) | [ReactJS/installation](https://reactjs.org/docs/installation.html#creating-a-new-application) | 2 hours  |

### Tasks :

* Add

## JavaScript XML Syntax

### Resources

| Concept |                      Best Video Resource                       |                            Best Text Resource                             |                        Documentation                         | Duration |
| :------ | :------------------------------------------------------------: | :-----------------------------------------------------------------------: | :----------------------------------------------------------: | :------: |
| JSX     | [EggHead](https://egghead.io/lessons/react-use-jsx-with-react) | [ReactEnlightment](https://www.reactenlightenment.com/react-jsx/5.1.html) | [ReactJS/jsx](https://reactjs.org/docs/introducing-jsx.html) | 6 hours  |

# Components

## Custom Components

### Resources

| Concept           |                            Best Video Resource                             |                                    Best Text Resource                                     |                              Documentation                               | Duration |
| :---------------- | :------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: | :----------------------------------------------------------------------: | :------: |
| Custom components | [EggHead](https://egghead.io/lessons/react-create-custom-react-components) | [ReactArmory](https://reactarmory.com/guides/learn-react-by-itself/custom-react-elements) | [ReactJS/components](https://reactjs.org/docs/components-and-props.html) | 8 hours  |

### Tasks :

* Add

## Rendering

### Resources

| Concept             |                                 Best Video Resource                                  |                                      Best Text Resource                                       |                                 Documentation                                  | Duration |
| :------------------ | :----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :------: |
| Rendering component | [EggHead](https://egghead.io/lessons/egghead-conditionally-render-a-react-component) | [ReactArmory](https://reactarmory.com/guides/learn-react-by-itself/rendering-and-rerendering) | [ReactJS/rendering-elements](https://reactjs.org/docs/rendering-elements.html) | 4 hours  |

### Tasks :

* Add

## Conditional Rendering

### Resources

| Concept             |                                 Best Video Resource                                  |                            Best Text Resource                             |                                   Documentation                                   | Duration |
| :------------------ | :----------------------------------------------------------------------------------: | :-----------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :------: |
| Rendering component | [EggHead](https://egghead.io/lessons/egghead-conditionally-render-a-react-component) | [RrobinWieruch](https://www.robinwieruch.de/conditional-rendering-react/) | [ReactJS/conditional-render](https://reactjs.org/docs/conditional-rendering.html) | 3 hours  |

### Tasks :

* Add

## Data flow

### Resources

| Concept         |                            Best Video Resource                             |                       Best Text Resource                       |                           Documentation                            | Duration |
| :-------------- | :------------------------------------------------------------------------: | :------------------------------------------------------------: | :----------------------------------------------------------------: | :------: |
| State and Props | [EggHead](https://egghead.io/lessons/react-use-component-state-with-react) | [LucyBain](http://lucybain.com/blog/2016/react-state-vs-pros/) | [ReactJS/state](https://reactjs.org/docs/state-and-lifecycle.html) | 8 hours  |

### Tasks :

* Add

## Lifecycle

### Resources

| Concept                     |                                  Best Video Resource                                   |                         Best Text Resource                         |         Documentation         | Duration |
| :-------------------------- | :------------------------------------------------------------------------------------: | :----------------------------------------------------------------: | :---------------------------: | :------: |
| Component Lifecycle methods | [Frontend Masters](https://frontendmasters.com/courses/react-intro/lifecycle-methods/) | [ReactArmory](https://reactarmory.com/guides/lifecycle-simulators) | [ReactJS/state-and-lifecycle] | 6 hours  |

### Tasks :

* Add

## Events

### Resources

| Concept        |                             Best Video Resource                             |                                   Best Text Resource                                   |                              Documentation                               | Duration |
| :------------- | :-------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :----------------------------------------------------------------------: | :------: |
| Events handler | [EggHead](https://egghead.io/lessons/egghead-use-event-handlers-with-react) | [JamesKNelson](https://reactarmory.com/guides/learn-react-by-itself/inputs-and-events) | [ReactJS/handling-events](https://reactjs.org/docs/handling-events.html) | 10 hours |

### Tasks :

* Add

# Forms

## Controlled Components

### Resources

| Concept          |                            Best Video Resource                            |                                    Best Text Resource                                    |                    Documentation                     | Duration |
| :--------------- | :-----------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :--------------------------------------------------: | :------: |
| Controlled forms | [EggHead](https://egghead.io/lessons/egghead-make-basic-forms-with-react) | [LorenStewart](https://lorenstewart.me/2016/10/31/react-js-forms-controlled-components/) | [ReactJS/forms](https://reactjs.org/docs/forms.html) | 8 hours  |

### Tasks :

* Add

## Uncontrolled Components

### Resources

| Concept            |                               Best Video Resource                                |                        Best Text Resource                        |                                 Documentation                                 | Duration |
| :----------------- | :------------------------------------------------------------------------------: | :--------------------------------------------------------------: | :---------------------------------------------------------------------------: | :------: |
| UnControlled forms | [EggHead](https://egghead.io/lessons/egghead-manipulate-the-dom-with-react-refs) | [LeftDevel](http://leftdevel.com/blog/reactjs-controlled-forms/) | [ReactJS/uncontrolled](https://reactjs.org/docs/uncontrolled-components.html) | 8 hours  |

### Tasks :

* Add

<!-- ## Basics

* Communicating Between Components
  * Parent To Child using 'props'
  * Child To Parent using 'callbacks'
* Stateless Functional Components
* Controlled & Uncontrolled Inputs
* Create a simple login form with React
* Accessing DOM Elements from React Components
* [Handling Errors](https://reactjs.org/docs/error-boundaries.html)
  Imperative vs Declarative
  Composition
  Virtual DOM
  children
  prop-types package
  createElement
  functional setState
  Container vs Presentational Components
  Stateless Functional Components
  Sytnthetic Events
  Private Stateless Functional Components

Working with Components

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
        Simulating Events -->
