# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Asynchronous code differs from synchronous code as it will continue to do it's task while other code can continue to be completed. This means that the whole browser won't freeze on a user while something like an API call takes place.

02. What is an event listener?

  > An event listener is an object that can be created that will listener to an event and then trigger a function. Within the MVC template we typically use the AppState.on method rather than DOM.addEventListener()

03. What does *REST* stand for, and in simple terms what does it mean??

  > REST stands for Representational state transfer, and in simple terms is a set of constraints/rules for designing an API in order for it to be "RESTful" which is good since many APIs are RESTful.

04. What is a callback / higher order function?

  > A callback function is a function that is called typically after another function has finished running.   

05. What is a `promise`? How do you capture an error from a `promise`?

  > A promise is something that gets returned from a function that will eventually resolve in an error or a success, but it is typically not the data you want to use. To capture an error from a promise, you can use a try catch block or a .then .catch block.

06. Name three processes used to make requests over `HTTP`?

  > GET, PUT, and POST are three processes used to make requests over HTTP

07. What does the `API` acronym stand for?

  > | Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?

  > You have to put async in the function signature.

09. What is the purpose of encapsulation in programming?

  > Encapsulation is meant to group similar data and methods and then choose which pieces are avaiable to another module/user. This allows data and methods to be hidden away, and the manipulation of the data be controlled.

10. What is `HTTP` response code for a successful request?

  > Code 200 is the response for a succesful request.

11. What is a 400 error?

  > A 400 error is a bad request error, meaning something is either incorrect in the request or missing from the request.
