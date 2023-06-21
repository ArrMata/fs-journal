# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > Foundationsof OOP is encapsulation and message passing.

02. How does `export` differ from `export default`?
  
  > Export default differs from export since if you were to import default values, `import math from ./xyz.js`, it will only be able to do that if you export default.

03. What is Encapsulation?
  
  > Encapsulation is grouping our data and how to manipulate our data so that we can choose what we specifically want to make public so our data and how's manipulated stays private and predictable.

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > The benefits of the Proxy object allows us to add functionality to existing on some basic operations for an Object class. Specifically for our applications, we can create private variables or allow only specific types to be set within our object.

05. What the difference between a `class` and an instance of a `class`?
  
  > Class acts more as a blueprint, rather than an instance of a class is a single built version of that class blueprint.

06. What is a computed Property?
  
  > A computed Property is a similar to a typical getting within a class, expect we computed on it beforehand, meaning that we can format/adjust the property as needed before we return it.

07. What is the purpose of the `MVC` pattern?
  
  > The purpose of the MVC design pattern, and design patterns in general, is to provide a structure/framework to where and how you write code. When you have that framework, it's easier to scale up the project without breaking many parts of existing code.

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > Controller is meant to both update the view and to notify the service to update the model.

09. What is the job of the `Service` in `MVC`?
  
  > The service directly interacts and updates the model.

10. What is the job of the `Model` in `MVC`?
  
  > Models within MVC act as our blueprint for how we want our data to be structured.