# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > it allows us to scope related objects and methods into a specific set. Our models and our repositories are in their own namespace scopes for example.

02. What is the difference between a `class` and an `interface`?

  > An interface only contains the definitions of the properties and methods a class should have but not the implementation. The class has both the implementation and definition. So a car interface can force all cars to have an engine. But all classes that are written for the interface can implement the engine all differently.

03. What is the method that returns an instance of a class, yet it has no return type?

  > The constructor method of a class.

04. No question 4 provided?

  >There was no question here, I didn't delete the question to sneak by!

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > public is the access modifier

06. In the Car example what is `string` an indication of?

  > The string is the type of what it returns.

07. In the Car example what is `abstract` preventing?

  > Abstract prevents the class from being instantiated.

08. In a SQL table, what is the difference between information in a row and information in a column?

  > Information in a row is a single entry into that table, filling out each column with the respective info required. Where as a single column has info about a single type, like an id column or a name column.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  ```
  CREATE TABLE characters(
    id int NOT NULL,
    name VARCHAR(255) NOT NULL,
    description VARCHAR(255),
    age int,
  )
  ```

10. In SQL how can you query more than a single table? Provide an example.

  > | ANSWER HERE |
