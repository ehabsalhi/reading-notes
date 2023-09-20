# Redux-ToolKit

> ## What concerns are addressed by Redux Toolkit?
>
> Redux Toolkit is designed to make Redux development more efficient, less error-prone, and more maintainable by addressing common concerns that Boilerplate Reduction, Simplified Store Configuration , Immutable Updates
> 
> ## What does configureStore() do?
>
> configureStore is a function provided by Redux Toolkit that simplifies the configuration of a Redux store.
> It offers simplified options and good defaults, automatically combines slice reducers, includes middleware like redux-thunk by default, it streamlines the process of setting up a Redux store.
> 
> ## How would I use createSlice()?
>
> To use createSlice function, provide reducers, a slice name, and an optional initial state. It generates a slice reducer, action creators, and types automatically, making Redux code shorter and simpler.
> 
> ## What is Mobx?
>
> MobX is a JavaScript library for managing state and the application's data flow in a reactive and efficient way.
> 
> ## How does MobX make it “impossible” to produce an inconsistent state?
>
> MobX ensures consistent state by automatically tracking and updating any value derived from the application state.
> 
> ## How would we build a reactive user interface?
>
> 1- To build a reactive user interface with MobX, you define observables to represent your state
> 
> 2- create actions or reactions to modify or observe the state, and use them in your components ,then the UI automatically updates in response to state changes.
