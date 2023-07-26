> # AWS: Events
> ## What is the difference betweeen SQS and SNS?
>
> SNS ( Simple Notification Service ) is a distributed publish-subscribe service ,fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients.
>  Amazon SNS makes it simple and cost effective to send push notifications to mobile device users, email recipients or even send messages to other distributed services
>
> SQS is distributed queuing service Amazon SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages.
>  Messages can be stored in SQS for short duration of time (max 14 days).

> 
> ## What are some use cases for both SNS and SQS?
>
> SNS supports several end points such as email, sms, http end point and SQS. If you want unknown number and type of subscribers to receive messages, you need SNS.
>
> SQS queue system, allowing decoupling of components and systems , and can be used as a task queue to manage asynchronous background tasks in applications .
> 
> ## Describe how to use SQS and SNS in a “fanout” pattern.
> Using SQS and SNS in a "fanout" pattern is a common architectural approach in distributed systems where a single message is broadcasted to multiple consumers (subscribers).
>  This pattern allows decoupling between publishers and subscribers, ensuring that each subscriber independently receives a copy of the message
> 
> ## Explain how “push notifications” work, using SNS.
>
> * create an SNS topic
> * Subscribing Endpoints to SNS topic
> * Endpoint Confirmation
> * Publishing Messages
> 
> ## How might a large scale, distributed application make use of a Queue system like SQS?
>
> By leveraging SQS as a central messaging service, large-scale distributed applications can achieve better scalability, fault tolerance, and loose coupling between components, making the application more resilient and easier to manage and maintain as it grows in complexity and scale.
