# react-redux-cheatsheet

It is *predictable* *state container* for *Javascript Apps*

1. It is for Javascript Apps.
1. It is a State container.
1. It is Predictable.


1. It is for Javascript Apps.
    - Redux is not tied to React
    - Can be used with React, Angular, Vue  or even Vanilla Javascript
    - Redux is library of Javascript applications

1. It is a State container.
    - Redux stores the state of your application
    - Consider a React app - state of a component
    - State of an app is the state represented by all the individual components of that app
    - Redux will store and manage the application state

1. It is Predictable.
    - Predictable in what way?
    - Redux is a state container
    - The state of the application can change
    - Ex: todo list app - item (pending) → item (completed)
    - In redux, all state transitions are explicit and it is possible to keep track of them
    - The changes to your application's state become predictable.

## Do we really have problem?

React context - Prevents prop drilling
useContext + useReducer ?
Redux 1.0 - August 2015

> React-Redux is the official Redux Ul binding library for React

1. React is a library used to build user interfaces
1. Redux is a library for managing state in a predictable way in JavaScript applications
1. React-redux is a library that provides bindings to use React and Redux together in an application