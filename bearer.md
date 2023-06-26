> ## What is a JSON Web Token (JWT)?
>
> A JSON Web Token (JWT) is a compact and secure way of transmitting information between parties as a JSON object and used for authentication and authorization in web applications.
>
> ## When should we use JSON Web Tokens?
>
> can be used in various scenarios, particularly in stateless, token-based authentication systems. They are commonly used when there is a need for secure transmission of information between parties and when the server needs to authenticate and authorize clients.
>
> ## Claims are expected in which structural component of a JWT?
>
> Payload component of JWT
>
> # Are JWTs Secure?
>
> ## If I get a JWT and I can decode the payload, how can we call that secure?
>
> A JWT is secure because it is signed with a secret key. thats means anyone who want to decode the payload will not able to do that because to do taht he need to know the secret key. If you can decode the payload, it means that you know the secret key sure, which means that you are the intended recipient of the JWT.
>
> If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
>
> The sender and receiver must both know the secret key that is used to create and verify the signature.
>
> Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter : we must use a secure encryption method to encrypt the concatenated content, to ensures that even if the content is intercepted during transit, it remains unreadable and confidential, also choose a strong encryption algorithm and use an encryption tool or software to encrypt the content.
>
> # JWTs Explained
>
> ## Why use JWT?
> 
> JWTs provide a secure way for authentication, authorization, and secure information exchange, making them a preferred choice in web and application development.
>
> JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
>
> It  is a special box that contains important information for a specific task. It is compact, meaning it is small in size and doesn't take up much space. This allows for easy transmission and sharing between different systems.
>
> What are the three components (the structure) of a JWT signature?
>
> Header , Payload , Signature
>
> # Things I want to know more about:
>  Bearer Authorization
>
> # why this topic matters as it relates to what you are studying in this module?
>
> for securing the web app






