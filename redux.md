# Redux

>  ## What is the first principle of Redux?
> 
> Single source of truth , this means that the entire state of the application is stored in a single JavaScript object, often referred to as the "store."
> 
> ## what is a store and what do we use our reducers for within that store?
>
> The store in Redux is an object that holds the entire state of the application , it is the central hub where all your application's data is stored ,you can think of it as a big JavaScript object that contains all the data your application needs.
>
> Reducers are used within the store to update the state based on the actions dispatched by your application.
> 
> ## Name three Redux store methods given to us by createStore and describe their use.
>
> getState() : to retrieve the current state of the Redux store. It returns the current state object, representing the entire state tree of your application.
>
> The dispatch(action) method is used to send actions to the Redux store, triggering state updates through reducers. You dispatch actions whenever you want to change the state in your Redux store.
>
> subscribe(listener) to add a listener function that gets called whenever the state in the Redux store changes. It's like setting up a notification system for state changes.
> 
> ## Explain to a non-technical recruiter what combineReducers() does and why it is useful.
>
> The combineReducers function is a utility provided by Redux to manage complexity in large applications with multiple reducers. It takes an object where each key corresponds to a state slice, and each value is a reducer for that slice. It creates a new reducer that combines these reducers into a single function.
