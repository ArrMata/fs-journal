# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create Read Update Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Create - Post, Read - Get, Update - Put, Delete - Delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object Relational Mapping, we use Mongoose as our ORM.

04. Which two `HTTP` request types include a body?

  > The two requests are a Post and Put request.

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > 1: Synchronous 2: Asynchronous

06. What are the three types of data relationships? Provide an example of each.

  > One to One - Driver's Liscense only belongs to one person, a person can only have one driver's liscense. One to Many - one team has many players, and all of those players belong to that one team. Many to Many - a game can have many players, and all of those players can play many games.

07. What is middleware?

  > Middleware, for what we've been using it for, allows us to handle our requests objects before we interact with them with other backend code. Specifically we've been using the Auth0 Authprovider to add the userInfo to our request objects.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > 1: Client 2: Server

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > ?tag=winter (?key=value pattern)

10. What is a ***virtual property***?

  > Virtual properties are additional getters and setters that we can create that allow us to have additional functionality built into those getters and setters. With that additonal functionality, we can use these virutals to also search through our collections in MongoDB and append that item onto the object with the virutal property.
