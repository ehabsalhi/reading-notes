> ## What is the main intended use case for the useEffect hook?
>
> It is designed to manage side effects in functional components , Side effects like [ data fetching, DOM manipulation ]
>
> ## How does the effect’s logic interact with the component?
>
>  When your component is added to the DOM, React will run your setup function. After every re-render with changed dependencies, React will first run the cleanup function (if you provided it) with the old values, and then run your setup function with the new values. After your component is removed from the DOM, React will run your cleanup function.
> 
> ## What is the importance of the return value from the effect’s logic function?
>
> to perform any necessary cleanup when the effect is no longer needed and it provides a way to clean up after the effect
