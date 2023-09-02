# Context API
> ## Summarize the five principles for structuring state.
>
> 1- Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable.
> 
> 2- Avoid contradictions in state. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
> 
> 3- Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.
> 
> 4- Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
> 
> 5- Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.
> 
> ## What problem do Contexts aim to solve?
>
> Context lets the parent component make some information available to any component in the app , insted of using passing props to a lot of component ( prop drilling ) . 
>
> ## What is one technique to try before useContext?
>
> Start by passing props if the components are not trivial, it’s not unusual to pass a dozen props down through a dozen components.
> It may feel like a slog, but it makes it very clear which components use which data
> 
> ## What hook complements useContext for complex applications?
>
> It is common to use a reducer together with context to manage complex state and pass it down to distant components without too much hassle.
