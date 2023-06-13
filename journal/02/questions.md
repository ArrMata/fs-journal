# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > var, let and const.

02. What is the definition of a function?

    > It's a subprogram, or a something to call within your program that does a task.

03. What are the `SOLID` principles?

    > SOLID principles allow us to write more maintainable and scalable code in object oriented programming. Meaning we can easily fix or add to our code without introducing new bugs.
    > S - Single responsibility 
    > O - Open/Closed principle
    > L - Listov Substituion 
    > I - Interface segregation
    > D - Dependency inversion

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.splice(indexOf('pineapple'), 1);

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you.friends.push(them)
    > them.friends.push(you)

06. Give an example of a JavaScript `Conditional`:

    > an if statement is an example of a conditional

07. What is the main difference between `parameters` and `arguments`?

    > When definining a function's signature, the variables defined within the parentheses in that signature are the parameters. When calling a function, the variables passed into that call are the arguments.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > Using dev tools within Chrome, you can use the debugger which allows you to add breakpoints which can stop the code at the defined breakpoint.

09. What is the difference between a `primitive` value and a `reference` value?

    > The difference between a primitive and reference value is that when assigning a variable to a primitive value, you can manipulate that variable without affecting the original value. While when doing it with reference values, if you were to change that value it would change the original.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > `for (let i = -100; i < 101; i++){`
    > ` console.log(i)`
    > `}`  
