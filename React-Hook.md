> ## Summarize the five steps of thinking in react.
> 
> Step 1: Break the UI into a component hierarchy : Separating the UI into components, where each component matches one piece of your data model.
> 
> Step 2: Build a static version in React  : It’s often easier to build the static version first and add interactivity later.
 Building a static version requires a lot of typing and no thinking, but adding interactivity requires a lot of thinking and not a lot of typing.
>
> Step 3: Find the minimal but complete representation of UI state : make sure that where is a state and where is not in the application, so the states are a data that could be change multiple times overtime.
>
> Step 4: Identify where your state should live :  identify which component is responsible for changing this state, or owns the state , and decide where the state should live
>
> Step 5: Add inverse data flow : sending data upward in the hierarchy involves altering the state using data from children, causing the parent to render differently based on events occurring within those children components.
>
> ## What is one reason a local variable isn’t sufficient for managing a React component?
>
> When React renders this component a second time, it renders it from scratch—it doesn’t consider any changes to the local variables.
>
> Changes to local variables won’t trigger renders. React doesn’t realize it needs to render the component again with the new data.
> 
> ## What is the argument to the useState hook ?
>
> 1-  The argument to the useState hook is the initial value of the state variable
>
> ## what are the two parts of useState return array?
> 
> 2- The current state value and a function to update the state value.
> 
> ## How can Component A access state from Component B?
> 
> using props
