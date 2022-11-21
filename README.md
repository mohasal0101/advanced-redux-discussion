
# Readings: Redux Advance

Below you will find some reading material and some additional resources that support today's topic and the upcoming lecture.

### Preparation Materials

-   [Reducers and Actions](https://medium.com/geekculture/understanding-createslice-in-redux-toolkit-reactjs-eca8d20f45d7 "https://medium.com/geekculture/understanding-createslice-in-redux-toolkit-reactjs-eca8d20f45d7")
-   [Redux Toolkit](https://redux.js.org/redux-toolkit/overview "https://redux.js.org/redux-toolkit/overview")
-   [createSlice](https://redux-toolkit.js.org/api/createslice "https://redux-toolkit.js.org/api/createslice")


### Redux

Redux is a JavaScript open-source library for managing application state. It is most commonly used for building user interfaces with libraries such as React or Angular.

Redux **Toolkit** was created with the intention of becoming the standard way to write redux logic. It is described as an opinionated, all-inclusive toolset for efficient Redux development. You can use this to write all of the code for your Redux store in a single file, including actions and reducers. You can use this to make your code more readable. The Redux toolkit contains all of the tools required to create a Redux application. In the end, all you have is less code and faster Redux setups in every scenario.


### createSlice

createSlice is a higher order function that takes an initial state, an object containing reducer functions, and a slice name as parameters. It generates action creators and action types that correspond to the reducers and state automatically.

The createSlice method in Redux-Toolkit allows us to create a slice of the redux-store. This function is intended to reduce the boilerplate required to add data to redux in the traditional manner. It employs createAction and createReducer internally.

