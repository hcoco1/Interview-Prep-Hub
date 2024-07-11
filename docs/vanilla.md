## Vanilla JS Questions


### 1. **What is JavaScript?**

>JavaScript is a versatile and widely-used programming language primarily used for front-end web development. It allows developers to add interactivity and dynamic behavior to web pages.

### 2. **What is the difference between null and undefined?**

>`null` represents the intentional absence of any value. `undefined` is the default value of a variable that has been declared but not assigned a value.

### 3. **Explain the concept of closures in JavaScript.**
>A closure is a function that retains access to variables from its outer (enclosing) function even after the outer function has finished executing. This allows the inner function to continue referencing those variables.

### 4. **What is the purpose of the this keyword in JavaScript?**
>The `this` keyword refers to the context in which a function is executed. It can be affected by how the function is called, and it helps to access properties and methods of an object.

### 5. **How does prototypal inheritance work in JavaScript?**
>Objects in JavaScript can inherit properties and methods from other objects through their prototype chain. If a property or method is not found in the current object, JavaScript looks up the prototype chain to find it.

### 6. **Explain the event delegation pattern in JavaScript.**
>Event delegation involves attaching an event listener to a common ancestor of multiple elements, instead of attaching listeners to each individual element. This is useful for improving performance and handling dynamic content.

### 7. **What are the different data types in JavaScript?**
>JavaScript has primitive data types: `string`, `number`, `boolean`, `null`, `undefined`, and `symbol` (ES6). It also has a non-primitive data type: `object`.

### 8. **What is asynchronous programming in JavaScript?**
>Asynchronous programming allows tasks to run in the background while the main program continues to execute. This is crucial for handling tasks like network requests, timers, and user input without blocking the main thread.

### 9. **What is the purpose of the bind, call, and apply methods?**
>These methods are used to control the value of the `this` keyword when calling a function. `bind` creates a new function with a fixed `this` value. `call` and `apply` immediately invoke the function with the provided `this` value and arguments.

### 10. **How can you handle errors in JavaScript?**
>JavaScript provides the `try...catch` statement for handling runtime errors. Code inside the `try` block is executed, and if an exception is thrown, it's caught and processed in the `catch` block.

### 11. **What are the differences between Java and JavaScript?**

>JavaScript is a client-side scripting language and Java is object Oriented Programming language. Both of them are totally different from each other.

>**JavaScript**: It is a light-weighted programming language (“scripting language”) for developing interactive web pages. It can insert dynamic text into the HTML elements. JavaScript is also known as the browser’s language.

>**Java**: Java is one of the most popular programming languages. It is an object-oriented programming language and has a virtual machine platform that allows you to create compiled programs that run on nearly every platform. Java promised, “Write Once, Run Anywhere”.

### 12. **Which symbol is used for comments in JavaScript?**

>Comments prevent the execution of statements. Comments are ignored while the compiler executes the code. There are two type of symbols to represent comments in JavaScript:

>Double slash: It is known as a single-line comment.

    `// Single line comment`

>Slash with Asterisk: It is known as a multi-line comment.
   
    /* 
    Multi-line comments
    ...
    */

### 13. **What would be the result of 3+2+”7″?**

> Here, 3 and 2 behave like an integer, and “7” behaves like a string. So 3 plus 2 will be 5. Then the output will be 5+”7″ = 57.






