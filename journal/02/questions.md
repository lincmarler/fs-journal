# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > The keywords are var, let, and const

02. What is the definition of a function?

    > A set of procedures that perform a certain task

03. What are the `SOLID` principles?

    > Single responsibility, open/closed, liskov substitution, interface segregation, dependency inversion.

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > console.log(fruit[2])

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

    > friends: [them.them]
    friends: [you.you]

06. Give an example of a JavaScript `Conditional`:

    > function getPaid(client){
        return client ? '$1.00' : '$15.00'
    }

07. What is the main difference between `parameters` and `arguments`?

    > A parameter is a variable in a method definition. When the mehtod is called the arguments are what you run through the method

08. Instead of writing everything to the console, what is a better way to debug your code?

    > The debugger tool

09. What is the difference between a `primitive` value and a `reference` value?

    > Primitive values are pieces of data while reference values are objects that could contain more than one value

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i=-100, i<=100, i++){
        console.log(i)
    }
