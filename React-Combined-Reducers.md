# Redux - Combined Reducers

> ## Why create multiple reducers?
>
> for managing different parts of the application state separately.
> 
> ## How would you combine multiple reducers?
>
> using combineReducers that provided by redux
> 
> ## How will you manage state as an immutable object? why?
>
>  This immutability helps to debugging, time-travel debugging , and avoiding unintended side effects.
> 
> ## combineReducers is a utility function to simplify the most common use case when writing multiple reducers .
> 
> ## Explain how combineReducers assembles the new state tree.
>
> In order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.
> So, in that sense, using combineReducers does "call all reducers", or at least all of the slice reducers it is wrapping.
> 
> ## How would you define initial state in an app using combineReducers?
>
> 1- the createStore function can take preloadedState as its second argument.
>
> 2- The other way is for the root reducer to return the initial state value when the state argument is undefined.
> 
> ## Why will you want to split your reducing functions as your app becomes more complex?
>
> Each reducer can be responsible for a specific feature or aspect of the application, which makes it easier to manage and extend as the application's complexity grows,
> also smaller reducers can be more easily reused across different parts of the application .
> 
> ## The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to create store .
>
> 
> ## What is a popular convention when naming reducers ?
>
> is to use a clear and descriptive naming pattern that indicates the slice of state they manage
