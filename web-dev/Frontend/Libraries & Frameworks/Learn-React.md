# ReactJS

# Curriculum

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Preface](#preface)
  - [Prerequities](#prerequities)
  - [Choosing ReactJS ?](#choosing-reactjs-)
  - [Philosophy](#philosophy)
- [Getting Started](#getting-started)
  - [Trying React](#trying-react)
  - [Create React App](#create-react-app)
  - [JavaScript XML Syntax](#javascript-xml-syntax)
- [Components](#components)
  - [Custom Components](#custom-components)
  - [Rendering](#rendering)
  - [Conditional Rendering](#conditional-rendering)
  - [Data flow](#data-flow)
  - [Lifecycle](#lifecycle)
  - [Events](#events)
- [Forms](#forms)
  - [Controlled Components](#controlled-components)
  - [Uncontrolled Components](#uncontrolled-components)
- [Composition](#composition)
  - [Lifting state up](#lifting-state-up)
  - [Composition vs Inheritance](#composition-vs-inheritance)
  - [Context](#context)
- [Tools](#tools)
  - [Developer Tools](#developer-tools)
  - [Proptypes](#proptypes)
  - [Error Boundaries](#error-boundaries)
- [In depth discussions](#in-depth-discussions)
  - [JSX in depth](#jsx-in-depth)
  - [Synthetic Events](#synthetic-events)
  - [React Without JSX](#react-without-jsx)
  - [React without ES6](#react-without-es6)
  - [Reconcilation - Diff Algorithm](#reconcilation---diff-algorithm)

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
* Install serve by `npm i -g serve` and `serve build` to test the appliction that you built.

## JavaScript XML Syntax

### Resources

| Concept |                      Best Video Resource                       |                            Best Text Resource                             |                        Documentation                         | Duration |
| :------ | :------------------------------------------------------------: | :-----------------------------------------------------------------------: | :----------------------------------------------------------: | :------: |
| JSX     | [EggHead](https://egghead.io/lessons/react-use-jsx-with-react) | [ReactEnlightment](https://www.reactenlightenment.com/react-jsx/5.1.html) | [ReactJS/jsx](https://reactjs.org/docs/introducing-jsx.html) | 6 hours  |

### Tasks :

* Add

# Components

## Custom Components

### Resources

| Concept           |                            Best Video Resource                             |                                    Best Text Resource                                     |                              Documentation                               | Duration |
| :---------------- | :------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: | :----------------------------------------------------------------------: | :------: |
| Custom components | [EggHead](https://egghead.io/lessons/react-create-custom-react-components) | [ReactArmory](https://reactarmory.com/guides/learn-react-by-itself/custom-react-elements) | [ReactJS/components](https://reactjs.org/docs/components-and-props.html) | 8 hours  |

### Tasks :

* Create a modified `h1` tag which has underline and blue colored text. You should be able to use it as `<Modh1>Some text</Modh1>` 

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

## Data flow

### Resources

| Concept         |                            Best Video Resource                             |                       Best Text Resource                       |                           Documentation                            | Duration |
| :-------------- | :------------------------------------------------------------------------: | :------------------------------------------------------------: | :----------------------------------------------------------------: | :------: |
| State and Props | [EggHead](https://egghead.io/lessons/react-use-component-state-with-react) | [LucyBain](http://lucybain.com/blog/2016/react-state-vs-pros/) | [ReactJS/state](https://reactjs.org/docs/state-and-lifecycle.html) | 8 hours  |

### Tasks :

* Create a BMI calculator application. 
    - This should internally contain two components, inputs for height and weight. 
    - Display the result in the BMI component itself.
    - We should be able to use it as `<BMICalc />`

## Lifecycle

### Resources

| Concept                     |                                  Best Video Resource                                   |                         Best Text Resource                         |         Documentation         | Duration |
| :-------------------------- | :------------------------------------------------------------------------------------: | :----------------------------------------------------------------: | :---------------------------: | :------: |
| Component Lifecycle methods | [Frontend Masters](https://frontendmasters.com/courses/react-intro/lifecycle-methods/) | [ReactArmory](https://reactarmory.com/guides/lifecycle-simulators) | [ReactJS/state-and-lifecycle] | 6 hours  |

### Tasks :

* Build an application which has a search bar. When we enter any Github username in it, show the user's details in a card below.
  - The card should make use of all the component lifecycle methods.

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

# Composition

## Lifting state up

### Resources

| Concept       |                  Best Video Resource                   |                              Best Text Resource                              |                              Documentation                              | Duration |
| :------------ | :----------------------------------------------------: | :--------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :------: |
| Lifting state | [Youtube](https://www.youtube.com/watch?v=a9pr1K2ueuA) | [Gerardnico](https://gerardnico.com/wiki/lang/javascript/react/shared_state) | [ReactJS/lifting-state](https://reactjs.org/docs/lifting-state-up.html) | 2 hours  |

### Tasks:

* as

## Composition vs Inheritance

### Resources

| Concept                    |                   Best Video Resource                   |                          Best Text Resource                           |                                   Documentation                                   | Duration |
| :------------------------- | :-----------------------------------------------------: | :-------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :------: |
| composition vs inheritance | [ViennaJS](https://www.youtube.com/watch?v=3Wo7InXlLfw) | [Brew](http://blog.brew.com.hk/react-101-composition-vs-inheritance/) | [ReactJS/comp-vs-inher](https://reactjs.org/docs/composition-vs-inheritance.html) | 1 hours  |

### Tasks:

* Advanced

## Context

### Resources

| Concept |                   Best Video Resource                    |                                       Best Text Resource                                       |                      Documentation                       | Duration |
| :------ | :------------------------------------------------------: | :--------------------------------------------------------------------------------------------: | :------------------------------------------------------: | :------: |
| Context | [ReactCast](https://www.youtube.com/watch?v=lxq938kqIss) | [JSPlayground](https://javascriptplayground.com/blog/2017/02/context-in-reactjs-applications/) | [ReactJS/context](https://reactjs.org/docs/context.html) | 4 hours  |

### Tasks:

* Advanced

# Tools

## Developer Tools

### Resources

| Concept                |                  Best Video Resource                   |                                      Best Text Resource                                      |                                     Documentation                                      | Duration |
| :--------------------- | :----------------------------------------------------: | :------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------: |
| Dev tools & Experience | [Youtube](https://www.youtube.com/watch?v=qXVakfdA040) | [Facebook/React-DevTools](https://github.com/facebook/react-devtools#react-developer-tools-) | [ReactJS/dev-ex](https://reactjs.org/docs/design-principles.html#developer-experience) | 1 hours  |

### Tasks :

* Add

## Proptypes

### Resources

| Concept   |                                       Best Video Resource                                        |                           Best Text Resource                            |                                  Documentation                                  | Duration |
| :-------- | :----------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :-----------------------------------------------------------------------------: | :------: |
| PropTypes | [EggHead](https://egghead.io/lessons/react-validate-custom-react-component-props-with-proptypes) | [Facebook/PropTypes](https://github.com/facebook/prop-types#prop-types) | [ReactJS/prop-types](https://reactjs.org/docs/typechecking-with-proptypes.html) | 1 hours  |

### Tasks :

* Add

## Error Boundaries

### Resources

| Concept          |                                      Best Video Resource                                      |                      Best Text Resource                      |                               Documentation                                | Duration |
| :--------------- | :-------------------------------------------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------------------------------: | :------: |
| Error Boundaries | [EggHead](https://egghead.io/lessons/react-error-handling-using-error-boundaries-in-react-16) | [Bugsnag](https://blog.bugsnag.com/react-16-error-handling/) | [ReactJS/error-boundaries](https://reactjs.org/docs/error-boundaries.html) | 1 hours  |

### Tasks :

* Add

# In depth discussions

## JSX in depth

### Resources

| Concept        |                 Best Video Resource                 |                            Best Text Resource                             |                        Documentation                         | Duration |
| :------------- | :-------------------------------------------------: | :-----------------------------------------------------------------------: | :----------------------------------------------------------: | :------: |
| JSX in details | [EggHead](https://egghead.io/lessons/jsx-deep-dive) | [PoonyFo](https://ponyfoo.com/articles/react-jsx-and-es6-the-weird-parts) | [ReactJS/jsx-in](https://reactjs.org/docs/jsx-in-depth.html) | 12 hours |

### Tasks :

## Synthetic Events

### Resources

| Concept      |                  Best Video Resource                   | Best Text Resource | Documentation | Duration |
| :----------- | :----------------------------------------------------: | :----------------: | :-----------: | :------: |
| React events | [Youtube](https://www.youtube.com/watch?v=dRo_egw7tBc) |                    |               | 12 hours |

### Tasks :

* Add

## React Without JSX

### Resources

| Concept           |                 Best Video Resource                 |                           Best Text Resource                           |                           Documentation                           | Duration |
| :---------------- | :-------------------------------------------------: | :--------------------------------------------------------------------: | :---------------------------------------------------------------: | :------: |
| React without JSX | [EggHead](https://egghead.io/lessons/jsx-deep-dive) | [Brain Mock](https://mockbrian.com/blog/2017/08/11/react-without-jsx/) | [ReactJS/no-jsx](https://reactjs.org/docs/react-without-jsx.html) | 2 hours  |

### Tasks :

* Add

## React without ES6

### Resources

| Concept           |                   Best Video Resource                    |                                  Best Text Resource                                  |                           Documentation                           | Duration |
| :---------------- | :------------------------------------------------------: | :----------------------------------------------------------------------------------: | :---------------------------------------------------------------: | :------: |
| React without es6 | [LiveCodin](https://www.youtube.com/watch?v=go1DilUf2a8) | [Medium](https://medium.com/@clmyles/react-without-npm-babel-or-webpack-1e9a6049714) | [ReactJS/no-es6](https://reactjs.org/docs/react-without-es6.html) | 2 hours  |

### Tasks :

* Add

## Reconcilation - Diff Algorithm

### Resources

| Concept       |                                                 Best Video Resource                                                 |                                         Best Text Resource                                         |                             Documentation                             | Duration |
| :------------ | :-----------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------: | :------: |
| Reconcilation | [Chariot Solutions](https://chariotsolutions.com/screencast/philly-ete-2016-30-jim-sproch-react-js-reconciliation/) | [Medium](https://medium.com/@gethylgeorge/how-virtual-dom-and-diffing-works-in-react-6fc805f9f84e) | [ReactJS/Reconcilation](https://reactjs.org/docs/reconciliation.html) | 10 hours |

### Tasks :

* Add
