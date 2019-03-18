# Week 8

## Monday: Redux

- mulitple pieces of state in multiple places
- "Redux attempts to make state mutations predictable by imposing certain restrictions on how and when updates can happen." [^1]
- `Store` is where you data is. Dispatch actions -> reducers -> change the store
- `Store`: whatever you want. Often a multi-layered object. Only **1** per application
- `Action`: Describes what happened. Plain JS object with at least a type as well as some data. Also have `action creators`
- `Reducer`: function that ties actions and state together. takes state and action as arguments, and returns the next state of the app. Must be **pure**
- Data flow: **strict unidirectional data flow** - dispatch actions to store, receive updated state from store

  1. You call `store.dispatch(action)`
  2. The Redux store calls the reducer function you gave it.
  3. The root reducer may combine the output of multiple reducers into a single state tree.
  4. The Redux store saves the complete state tree returned by the root reducer.

[^1]: [Redux: Motivation](https://redux.js.org/introduction/motivation)

### Todo List

### Resources
