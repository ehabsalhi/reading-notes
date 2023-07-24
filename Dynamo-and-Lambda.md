> # Readings: AWS: API, Dynamo and Lambda
>
> ## What is Amazon API Gateway?
>
> Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
>
> ## Why is Amazon API Gateway an important part of the Serverless ecosystem?
>
> API Gateway is the piece that ties together Serverless functions and API definitions.
> Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.
> 
> ## How does API Gateway integrate with other AWS services?
>
> API Gateway integrates with many other AWS services like AWS Lambda, AWS SNS, AWS IAM, and Cognito Identity Pools. These integrations allow for fully managed authentication and authorization layers, as well as detailed metrics and tracing for API requests.
>
> ## What are the some benefits of using Amazon API Gateway?
>
> * Run multiple versions of the same API simultaneously with API Gateway, allowing you to quickly iterate, test, and release new versions.
> * Monitor performance metrics and information on API calls, data latency, and error rates from the API Gateway dashboard
> * Authorize access to your APIs with AWS Identity and Access Management (IAM) and Amazon Cognito.
> * Create RESTful APIs using HTTP APIs or REST APIs
>
> ## What two API types might you choose from?
>
> * RESTful APIs
> * WEBSOCKET APIs
>   
> ## What is DynamoDB?
>
> DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)
> 
> ## Under what circumstances would you recommend DynamoDB over MongoDB?
>
> * Applications with large amounts of data and strict latency requirements.
> * Serverless applications using AWS Lambda
> * Data sets with simple, known access patterns.
>
> ## Explain to a non-technical friend how DynamoDB works.
>
> Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data import and export tools.
>
> ## What is Dynamoose?
>
> Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose .
>
> ## What are some key features of Dynamoose?
>
> * Type safety
> * High level API
> * Easy to use syntax
> * DynamoDB Single Table Design Support
> * Ability to transform data before saving or retrieving items
> * Strict data modeling (validation, required attributes, and more)
> * Support for DynamoDB Transactions
> * Powerful Conditional/Filtering Support
> * Callback & Promise support
> * AWS Multi-region support

