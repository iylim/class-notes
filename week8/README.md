# Week 8

## Wednesday: Redux

### Core Concepts

**Store**: Global application state. Can hold both data and UI state

**Actions**: Describes what happened. Plain JS object with at least a `type` as well as some data

**Reducers**: function that ties actions and state together. takes state and action as arguments, and returns the next state of the app. Must be **pure**, meaning _no_ side-effects (such as API calls)

Data flow: **strict unidirectional data flow** - dispatch actions to store, receive updated state from store

1. You call `store.dispatch(action)`
2. The Redux store calls the reducer function you gave it.
3. The root reducer may combine the output of multiple reducers into a single state tree.
4. The Redux store saves the complete state tree returned by the root reducer.

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
- Containers vs presentational components
- Containers:
  1. `mapStateToProps`: describes how to transform the current Redux store state into the props you want to pass to a presentational component you are wrapping
  2. `mapDispatchToProps`: receives the `dispatch()` method and returns callback props that you want to inject into the presentational component
  3. `connect()`: returns a [HOC](https://reactjs.org/docs/higher-order-components.html)

[^1]: [Redux: Motivation](https://redux.js.org/introduction/motivation)

### Trello, World

1. Explain data model:
   ```js
   {
     cards: [
       {
         text,
         board
       }
     ],
     boards: [ 'name' ]
   }
   ```
2. actions
   1. card
   2. board
3. reducers
   1. First as one giant function, then compose it out
   2. root
   3. card
   4. board
4. create `Main` with `mapStateToProps` and connect
5. create store with default state and pass to `Provider`
6. create `Board` with `mapStateToProps` and `matchDispatchToProps` and connect
   1. map cards
   2. pass addcard to form
7. Form
   1. submission with addCard
8. Card
   1. deletion with removeCard

### Resources
