# ReactJS

# Curriculum

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Preface](#preface)
  * [Prerequities](#prerequities)
  * [Choosing ReactJS ?](#why-reactjs)
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
* [Composition](#composition)
  * [Lifting state up](#lifting-state-up)
  * [Composition vs Inheritance](#composition-vs-inheritance)
  * [Context](#context)
* [Hooks](#hooks)
  * [Introduction](#hooks-introduction)
  * [Predefined hooks](#predefined-hooks)
  * [Writing Custom Hooks](#custom-hooks)
* [Tools](#tools)
  * [Developer Tools](#developer-tools)
  * [PropTypes](#proptypes)
  * [Error Boundaries](#error-boundaries)
* [In depth discussions](#in-depth-discussions)
  * [JSX in depth](#jsx-in-depth)
  * [Synthetic Events](#synthetic-events)
  * [React Without JSX](#react-without-jsx)
  * [React without ES6](#react-without-es6)
  * [Reconciliation - Diff Algorithm](#reconciliation---diff-algorithm)
* [Courses](#courses)
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Preface

## Prerequisites

Experience with the basic web technologies i.e. HTML, CSS & JavaScript will help. Having a good grasp on ES6 / ES7 & functional JavaScript is essential. 

## Why ReactJS ?

React is an open source JavaScript library for building user interfaces by Facebook Inc.

* **View in MVC** – ReactJS acts as the view layer for your application and it provides a robust infrastructure to build scalable and performant front ends.

* **Virtual DOM** – This is probably why most developers are so attracted to React. React manages its own DOM in memory. The most expensive operation most web apps suffer is mutating the DOM. React's approach is to maintain a virtual representation of the DOM which allows it to calculate differences in the DOM so that it only mutates the part of the DOM that actually needs to be updated. This is a huge benefit!

* **Declarative** – Design simple views for each state in your application, and React provides an innovating abstraction layer which efficiently updates just the right components when your data changes.

* **Component-Based** – Build encapsulated components that manage their own state, then compose them to make complex UIs.

* **Server Side Rendering** – Combining a NodeJS server and ReactJS helps us build even more complex applications by pre-rendering the initial state of our ReactJS components.

* **JavaScript** – It is JavaScript after all. We can use latest JavaScript goodies by transpiling our code with the tools we prefer like webpack, browserify, rollup, babel etc

* **Non-Opinionated** – It doesn't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code.

* **Testability** – React components simplify testing greatly. As a proof of it's simplicity, our new web client has more tests than any of our other clients.

* **Functional Programming** – ReactJS stateless components act like pure functions while composition is highly enforced instead of inheritance to reuse code between components.

## Philosophy

### Resources

| Concept                   |                   Best Video Resource                    |                                     Best Text Resource                                     |                                Documentation                                 | Duration |
| :------------------------ | :------------------------------------------------------: | :----------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :------: |
| Best practices with react | [JSConf EU](https://www.youtube.com/watch?v=x7cQ3mrcKaY) | [Medium](https://medium.com/@nimelrian/thinking-in-react-a-paradox-statement-33c19e2eb9e2) | [ReactJS/thinking-in-react](https://reactjs.org/docs/thinking-in-react.html) | 1 hours  |

### Tasks :

* Take an application like Instagram and plan on what parts of it are re-usable and make a component.

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

* Use `create-react-app` and create a sample React app.
* Convert km to miles converter that you built previously into this application that you created now.
* Build the application using `create-react-app`
* Install serve by `npm i -g serve` and `serve build` to test the application that you built.

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

* Create a modified `h1` tag which has underline and blue colored text. You should be able to use it as `<Modh1>Some text</Modh1>`

#### Additional Tasks:
- Build a simple markdown app
- Make a carousel
- Make any component that you find will accelerate your work, like
  - A table component to quickly create tables
  - A responsive menu component
  - Anything else you could think of!
- A simple TODO APP

## Rendering

### Resources

| Concept             |                                 Best Video Resource                                  |                                      Best Text Resource                                       |                                 Documentation                                  | Duration |
| :------------------ | :----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :------: |
| Rendering component | [EggHead](https://egghead.io/lessons/egghead-conditionally-render-a-react-component) | [ReactArmory](https://reactarmory.com/guides/learn-react-by-itself/rendering-and-rerendering) | [ReactJS/rendering-elements](https://reactjs.org/docs/rendering-elements.html) | 4 hours  |

### Tasks :

* Create an Time Application which updates automatically and always shows the current time. Time should be in the format `HH:MM:SS AM/PM`.

## Conditional Rendering

### Resources

| Concept             |                                 Best Video Resource                                  |                            Best Text Resource                             |                                   Documentation                                   | Duration |
| :------------------ | :----------------------------------------------------------------------------------: | :-----------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :------: |
| Rendering component | [EggHead](https://egghead.io/lessons/egghead-conditionally-render-a-react-component) | [RrobinWieruch](https://www.robinwieruch.de/conditional-rendering-react/) | [ReactJS/conditional-render](https://reactjs.org/docs/conditional-rendering.html) | 3 hours  |

### Tasks :

* Create an application with component `<Greet />` which displays "Good morning/evening/night" based on the time.
* Create a website where you show different images based on the user input
  - Examples would be a user selecting a car type, and you display car images depending on the user input. 
* Create a website which only displays a page if you enter the right password, you don't need to implement the backend!

## Data flow

### Resources

| Concept         |                            Best Video Resource                             |                       Best Text Resource                       |                           Documentation                            | Duration |
| :-------------- | :------------------------------------------------------------------------: | :------------------------------------------------------------: | :----------------------------------------------------------------: | :------: |
| State and Props | [EggHead](https://egghead.io/lessons/react-use-component-state-with-react) | [LucyBain](http://lucybain.com/blog/2016/react-state-vs-pros/) | [ReactJS/state](https://reactjs.org/docs/state-and-lifecycle.html) | 8 hours  |

### Tasks :

* Create a BMI calculator application.
  * This should internally contain two components, inputs for height and weight.
  * Display the result in the BMI component itself.
  * We should be able to use it as `<BMICalc />`

## Lifecycle

### Resources

| Concept                     |                                  Best Video Resource                                   |                         Best Text Resource                         |                                  Documentation                                   | Duration |
| :-------------------------- | :------------------------------------------------------------------------------------: | :----------------------------------------------------------------: | :------------------------------------------------------------------------------: | :------: |
| Component Lifecycle methods | [Frontend Masters](https://frontendmasters.com/courses/react-intro/lifecycle-methods/) | [ReactArmory](https://reactarmory.com/guides/lifecycle-simulators) | [ReactJS/state-and-lifecycle](https://reactjs.org/docs/state-and-lifecycle.html) | 6 hours  |

### Tasks :

* Build an application which has a search bar. When we enter any GitHub username in it, show the user's details in a card below.
  * The card should make use of all the component lifecycle methods.

## Events

### Resources

| Concept        |                             Best Video Resource                             |                                   Best Text Resource                                   |                              Documentation                               | Duration |
| :------------- | :-------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :----------------------------------------------------------------------: | :------: |
| Events handler | [EggHead](https://egghead.io/lessons/egghead-use-event-handlers-with-react) | [JamesKNelson](https://reactarmory.com/guides/learn-react-by-itself/inputs-and-events) | [ReactJS/handling-events](https://reactjs.org/docs/handling-events.html) | 10 hours |

### Tasks :

* Build a todo application with following requirements
  * Input field to add new todos
  * Click on todo to toggle completion. Maybe strikethrough if its completed.
  * Double click on a todo to delete it.

# Forms

## Controlled Components

### Resources

| Concept          |                            Best Video Resource                            |                                    Best Text Resource                                    |                    Documentation                     | Duration |
| :--------------- | :-----------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :--------------------------------------------------: | :------: |
| Controlled forms | [EggHead](https://egghead.io/lessons/egghead-make-basic-forms-with-react) | [LorenStewart](https://lorenstewart.me/2016/10/31/react-js-forms-controlled-components/) | [ReactJS/forms](https://reactjs.org/docs/forms.html) | 8 hours  |

### Tasks :

* Build an app which has a sign up form for students.
  * Year of passing should be dropdown and should contain only 5 years back from now.
  * Take in the date of birth and show his age next to dob input
  * Suggest a few interested topics to select from a list of suggestions. These suggestions should appear as a type-ahead.

## Uncontrolled Components

### Resources

| Concept            |                               Best Video Resource                                |                        Best Text Resource                        |                                 Documentation                                 | Duration |
| :----------------- | :------------------------------------------------------------------------------: | :--------------------------------------------------------------: | :---------------------------------------------------------------------------: | :------: |
| UnControlled forms | [EggHead](https://egghead.io/lessons/egghead-manipulate-the-dom-with-react-refs) | [LeftDevel](http://leftdevel.com/blog/reactjs-controlled-forms/) | [ReactJS/uncontrolled](https://reactjs.org/docs/uncontrolled-components.html) | 8 hours  |

### Tasks :

* Built an app that shows a red color rectangle using canvas elements.

# Composition

## Lifting state up

### Resources

| Concept       |                  Best Video Resource                   |                              Best Text Resource                              |                              Documentation                              | Duration |
| :------------ | :----------------------------------------------------: | :--------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :------: |
| Lifting state | [Youtube](https://www.youtube.com/watch?v=a9pr1K2ueuA) | [Gerardnico](https://gerardnico.com/wiki/lang/javascript/react/shared_state) | [ReactJS/lifting-state](https://reactjs.org/docs/lifting-state-up.html) | 2 hours  |

### Tasks:

* Create an application with an Image and like button as a child component. Have a count in the parent which has the Image. When we press like button, the count should be incremented.

## Composition vs Inheritance

### Resources

| Concept                    |                   Best Video Resource                   |                          Best Text Resource                           |                                   Documentation                                   | Duration |
| :------------------------- | :-----------------------------------------------------: | :-------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :------: |
| composition vs inheritance | [ViennaJS](https://www.youtube.com/watch?v=3Wo7InXlLfw) | [Brew](http://blog.brew.com.hk/react-101-composition-vs-inheritance/) | [ReactJS/comp-vs-inher](https://reactjs.org/docs/composition-vs-inheritance.html) | 1 hours  |

### Tasks:

* Create an application with a Sidebar component `<Sidebar></Sidebar>` which can take any number of other component/elements to display in the sidebar.

## Context

### Resources

| Concept |                   Best Video Resource                    |                                       Best Text Resource                                       |                      Documentation                       | Duration |
| :------ | :------------------------------------------------------: | :--------------------------------------------------------------------------------------------: | :------------------------------------------------------: | :------: |
| Context | [ReactCast](https://www.youtube.com/watch?v=lxq938kqIss) | [JSPlayground](https://javascriptplayground.com/blog/2017/02/context-in-reactjs-applications/) | [ReactJS/context](https://reactjs.org/docs/context.html) | 4 hours  |

### Tasks:

* In the todo app that you built previously built, change it to use context instead of props.
# Hooks 

## Hooks Introduction
 
### Resources

| Concept                |                  Best Video Resource                   |                                      Best Text Resource                                      |                                     Documentation                                      | Duration |
| :--------------------- | :----------------------------------------------------: | :------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------: |
| Glance at Hooks | [Youtube](https://www.youtube.com/watch?v=dpw9EHDh2bM) | [Freecodecamp](https://medium.freecodecamp.org/an-introduction-to-react-hooks-12843fcd2fd9) | [ReactJS Hooks](https://reactjs.org/docs/hooks-intro.html) | 1 hours  |


### Tasks:

* Change exising class comonents in todo app into functional components and use hooks instead of methods in Component.

## Predefined Hooks

### Resources

| Concept                |                  Best Video Resource                   |                                      Best Text Resource                                      |                                     Documentation                                      | Duration |
| :--------------------- | :----------------------------------------------------: | :------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------: |
| useState hook | [Youtube](https://www.youtube.com/watch?v=oGtKXuu7Mgk) | [freecodecamp](https://medium.freecodecamp.org/a-quick-introduction-to-the-react-state-hook-9910f298eefb) | [ React hooks](https://reactjs.org/docs/hooks-state.html) | 1 hours  |



### Tasks:

* Use useState() hook instead of state in class component in todo app.

## Custom Hooks

### Resources

| Concept                |                  Best Video Resource                   |                                      Best Text Resource                                      |                                     Documentation                                      | Duration |
| :--------------------- | :----------------------------------------------------: | :------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------: |
| custom hooks | [Youtube](https://www.youtube.com/watch?v=fnT5b2u1PHE) | [levelup](https://levelup.gitconnected.com/two-simple-reusable-custom-hooks-for-your-react-apps-a0275724f8ab) | [ Custom React hooks]([https://reactjs.org/docs/hooks-state.html](https://reactjs.org/docs/hooks-custom.html)) | 1 hours  |


### Tasks:

* Write a custom hook to make a api call and update state only if data changes from previous.

# Tools

## Developer Tools

### Resources

| Concept                |                  Best Video Resource                   |                                      Best Text Resource                                      |                                     Documentation                                      | Duration |
| :--------------------- | :----------------------------------------------------: | :------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------: |
| Dev tools & Experience | [Youtube](https://www.youtube.com/watch?v=qXVakfdA040) | [Facebook/React-DevTools](https://github.com/facebook/react-devtools#react-developer-tools-) | [ReactJS/dev-ex](https://reactjs.org/docs/design-principles.html#developer-experience) | 1 hours  |

### Tasks :

* Inspect [coderplex website](https://coderplex.org/) to know what all are components and details of them.

## Type System

### Resources

| Concept   |                                       Best Video Resource                                        |                           Best Text Resource                            |                                  Documentation                                  | Duration |
| :-------- | :----------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :-----------------------------------------------------------------------------: | :------: |
| PropTypes | [EggHead](https://egghead.io/lessons/react-validate-custom-react-component-props-with-proptypes) | [Facebook/PropTypes](https://github.com/facebook/prop-types#prop-types) | [ReactJS/prop-types](https://reactjs.org/docs/typechecking-with-proptypes.html) | 1 hours  |
| Flow |  | [Flow](https://flow.org/en/docs/getting-started/) | [Flow Documentation](https://flow.org/en/docs/) | 1 - 5 hours  |
| Typescript |  | [Typescript Starter Kit](https://github.com/Microsoft/TypeScript-React-Starter#typescript-react-starter) | [Typescript Handbook](http://www.typescriptlang.org/docs/handbook/basic-types.html) | 5 - 8 hours  |
### Tasks :

* Create an application similar with a component printer taking some text to display as a prop.
  * Use propTypes to check whether the prop passed is string or not.

## Error Boundaries

### Resources

| Concept          |                                      Best Video Resource                                      |                      Best Text Resource                      |                               Documentation                                | Duration |
| :--------------- | :-------------------------------------------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------------------------------: | :------: |
| Error Boundaries | [EggHead](https://egghead.io/lessons/react-error-handling-using-error-boundaries-in-react-16) | [Bugsnag](https://blog.bugsnag.com/react-16-error-handling/) | [ReactJS/error-boundaries](https://reactjs.org/docs/error-boundaries.html) | 1 hours  |

### Tasks :

* Create an application with an `<ErrorWrapper>` component which catches errors in its children components and displays an error message if some error occurs.
* Implement Error boundaries in most of the previous react applications you built. 

# In depth discussions

## JSX in depth

### Resources

| Concept        |                 Best Video Resource                 |                            Best Text Resource                             |                        Documentation                         | Duration |
| :------------- | :-------------------------------------------------: | :-----------------------------------------------------------------------: | :----------------------------------------------------------: | :------: |
| JSX in details | [EggHead](https://egghead.io/lessons/jsx-deep-dive) | [PoonyFo](https://ponyfoo.com/articles/react-jsx-and-es6-the-weird-parts) | [ReactJS/jsx-in](https://reactjs.org/docs/jsx-in-depth.html) | 12 hours |

## Synthetic Events

### Resources

| Concept      |                  Best Video Resource                   |                     Best Text Resource                     |                     Documentation                      | Duration |
| :----------- | :----------------------------------------------------: | :--------------------------------------------------------: | :----------------------------------------------------: | :------: |
| React events | [Youtube](https://www.youtube.com/watch?v=dRo_egw7tBc) | [Kirupa](https://www.kirupa.com/react/events_in_react.htm) | [ReactJS/Events](https://reactjs.org/docs/events.html) | 12 hours |

## React Without JSX

### Resources

| Concept           |                 Best Video Resource                 |                           Best Text Resource                           |                           Documentation                           | Duration |
| :---------------- | :-------------------------------------------------: | :--------------------------------------------------------------------: | :---------------------------------------------------------------: | :------: |
| React without JSX | [EggHead](https://egghead.io/lessons/jsx-deep-dive) | [Brain Mock](https://mockbrian.com/blog/2017/08/11/react-without-jsx/) | [ReactJS/no-jsx](https://reactjs.org/docs/react-without-jsx.html) | 2 hours  |

### Tasks :

* Create a stopwatch application without any JSX.

## React without ES6

### Resources

| Concept           |                   Best Video Resource                    |                                  Best Text Resource                                  |                           Documentation                           | Duration |
| :---------------- | :------------------------------------------------------: | :----------------------------------------------------------------------------------: | :---------------------------------------------------------------: | :------: |
| React without es6 | [LiveCodin](https://www.youtube.com/watch?v=go1DilUf2a8) | [Medium](https://medium.com/@clmyles/react-without-npm-babel-or-webpack-1e9a6049714) | [ReactJS/no-es6](https://reactjs.org/docs/react-without-es6.html) | 2 hours  |

### Tasks :

* Recreate the same stopwatch application without writing any ES6 code.

## Reconciliation - Diff Algorithm

### Resources

| Concept       |                                                 Best Video Resource                                                 |                                         Best Text Resource                                         |                             Documentation                             | Duration |
| :------------ | :-----------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------: | :------: |
| Reconciliation | [Chariot Solutions](https://chariotsolutions.com/screencast/philly-ete-2016-30-jim-sproch-react-js-reconciliation/) | [Medium](https://medium.com/@gethylgeorge/how-virtual-dom-and-diffing-works-in-react-6fc805f9f84e) | [ReactJS/Reconciliation](https://reactjs.org/docs/reconciliation.html) | 10 hours |

# Courses

- [The Beginner's Guide To React](https://egghead.io/courses/the-beginner-s-guide-to-react)
