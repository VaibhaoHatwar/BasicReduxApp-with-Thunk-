# Basic Redux App (with Thunk)

This is made to practice basic Redux with Thunk middleware.

## Redux

A Predictable State Container for JS Apps

### `Predictable`

Redux helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test.

### `Centralized`

Centralizing your application's state and logic enables powerful capabilities like undo/redo, state persistence, and much more.

### `Debuggable`

The Redux DevTools make it easy to trace when, where, why, and how your application's state changed. Redux's architecture lets you log changes, use "time-travel debugging", and even send complete error reports to a server.

### `Flexible`

Redux works with any UI layer, and has a large ecosystem of addons to fit your needs.

## React-Redux

Official React bindings for Redux

### `Official`

React Redux is maintained by the Redux team, and kept up-to-date with the latest APIs from Redux and React.

### `Predictable`

Designed to work with React's component model. You define how to extract the values your component needs from Redux, and your component updates automatically as needed.

### `Encapsulated`

Provides APIs that enable your components to interact with the Redux store, so you don't have to write that logic yourself.

### `Optimized`

Automatically implements complex performance optimizations, so that your own component only re-renders when the data it needs has actually changed.

## What is a "thunk"?

The word "thunk" is a programming term that means "a piece of code that does some delayed work". Rather than execute some logic now, we can write a function body or code that can be used to perform the work later.

For Redux specifically, "thunks" are a pattern of writing functions with logic inside that can interact with a Redux store's dispatch and getState methods.

Using thunks requires the redux-thunk middleware to be added to the Redux store as part of its configuration.

Thunks are the standard approach for writing async logic in Redux apps, and are commonly used for data fetching. However, they can be used for a variety of tasks, and can contain both synchronous and asynchronous logic.
