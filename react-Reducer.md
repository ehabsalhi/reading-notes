> ## What is the motivation for adding a reducer?
>
> for puting all the state update logic outside the component in a single function , by reducer you can avoid the overwhelming of components that have many of state updates spread across many event handlers .
> 
> ## What are actions in the context of a reducer? How are they different than setting state directly?
>
> actions are a JavaScript objects that describe a change that needs to be made to the application's state
>  
> ## What common list operation is useReduce named for, and why?
>
> they are actually named after the reduce() operation that you can perform on arrays
> 
> ## When should you switch from useState to useReducer?
>
> depends on the complexity of the structure of the application , and if the app has more complex logic or states , and if requires handling of various actions and transitions.
