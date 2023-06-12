# Express REST API

## [ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1- Classes are a template for creating objects.

2- Can a class declaration be hoisted?
* No ,it is not hoisted

3-How would you describe a constructor and contextual “this” to a non-technical friend?
* The constructor is a method inside the clase and we use it to create an object 
* acontextual 'This'  represents the current object or context that associated with it ,and in that way we can call this object by using 'this' .

## [Using Express Routing](https://expressjs.com/en/guide/routing.html)

1- Within Express, what does routing refer to?
* refers to how an application’s endpoints (URIs) respond to client requests.

2- What is the difference between a route path and a route method?
* route method it's one of HTTP methods, we use it to execute a specific function ,and route path we use it to define the endpoints at which requests can be made.

3- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
* we use next when we need to do a specific operation inside route handler and then pass control to the next one
* We must call it to pass control to the next handler ,also to make sure that the application is working normally

## [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)

1- What is an Express Router?
*  It is a mini express application contains only the routing stuff

2- By what mean do we initialize express.Router() in an express server?
*var router = express.Router();

3- What do we use route middleware for?
*to do something before given the information to the user , like checking if a user is authenticated .

## why this topic matters ?
* Classes : because it provide the foundation for creating objects and building complex and flexible software systems.

* Express Routing : to simplify web application , and helps developers handle different routes for their web applications.

## What are your learning goals after reading and reviewing the class [README ?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-03/)
* increase my understanding about OOP and Express Routing
