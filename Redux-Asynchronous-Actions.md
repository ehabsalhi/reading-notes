# Redux-Asynchronous-Actions

> ## Why use Redux middleware?
>
> Middleware allows to handle side effects, such as making API requests, interacting with a database, or logging ,and dealing with asynchronous actions.
> 
> ## Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
>
> It's explain how Redux manages the flow of data and actions in an application that have asynchronous operations.
> 
> ## How are we accommodating async in our Redux app?
>
> By using middleware that sits between the dispatching of an action and the moment it reaches the reducers, allow to handle asynchronous operations .
> 
> ## Why would you need redux-thunk middleware?
>
> to handle asynchronous operations, =a tool for managing side effects, handling API requests .
> 
> ## Redux Thunk middleware allows you to write action creators that return a function instead of an action.
> 
> ## Describe how any return value from the inner thunk function will be made available.
>
>  the inner thunk function uses the dispatch function to dispatch actions, and those actions, update the Redux store's state. 

