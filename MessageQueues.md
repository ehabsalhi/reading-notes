> # Readings: Message Queues
>
> ## 1- Explain to a non-technical recruiter what the Chat Example (above) does.
> 
> can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.
>
> ## 2- What proof of life are we getting on the backend from the above app?
>
> knowing how we can activate the socket and link it with the server also how we can dealing with it
>
> ## 3- Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
>
> Broadcast
>
> ## 4 -What is a room and how might a room be useful?
>
> A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients
>
> ## 5- How do you join a room?
>
> * You can call join to subscribe the socket to a given channel
> * And then simply use to or in when broadcasting or emitting .
>
> ## 6- how do you leave a room?
>
> To leave a channel you call leave
>
> ## 7- What is a Namespace and what does it allow you to do?
>
> allows you to split the logic of your application over a single shared connection (also called "multiplexing").
> 
> ## 8- Each namespace potentially has its own what? (hint: 3 things)
>
> * event handlers
> * Rooms
> * middlewares
> 
> ## 9- Discuss a possible use case for separate namespaces
>
> * to authorized users that have access to, so the logic related to those users is separated from the rest of the application
> * the application has multiple tenants so you want to dynamically create one namespace per tenant




