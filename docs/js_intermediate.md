# Level-2 : Intermediate

13. **What is Closure? What are the use cases of Closures?**
    - A closure is a function that retains access to its lexical scope even when the function is executed outside that scope. Use cases include data encapsulation, creating private variables, and function factories.

14. **Explain the concept of hoisting in JavaScript.**
    - Hoisting is JavaScript's default behavior of moving declarations (not initializations) to the top of their containing scope during compilation. `var` declarations are hoisted to the top of their function scope, while `let` and `const` declarations are hoisted to the top of their block scope but are not initialized.

15. **What is a Temporal Dead Zone?**
    - The Temporal Dead Zone (TDZ) is the time period between entering a scope and the actual declaration of a variable where accessing the variable will result in a `ReferenceError`.

16. **What is a prototype chain? and Object.create() method?**
    - The prototype chain is a series of linked prototypes. Every object has a prototype, and a prototype can have its own prototype, forming a chain. `Object.create(proto)` creates a new object with the specified prototype.

17. **What is the difference between Call, Apply, and Bind methods?**
    - `call`: Invokes a function with a specified `this` value and arguments provided individually.
    - `apply`: Invokes a function with a specified `this` value and arguments provided as an array.
    - `bind`: Returns a new function, permanently bound to the provided `this` value and initial arguments.

18. **What are lambda or arrow functions?**
    - Arrow functions are a concise syntax for writing functions using the `=>` arrow notation. They do not have their own `this` value and cannot be used as constructors.

19. **What is the currying function?**
    - Currying is the process of transforming a function that takes multiple arguments into a sequence of functions that each take a single argument.

20. **What are the features of ES6?**
    - Some key features of ES6 (ECMAScript 2015) include:
      - `let` and `const` declarations
      - Arrow functions
      - Template literals
      - Destructuring assignment
      - Default parameters
      - Rest and spread operators
      - Classes
      - Promises
      - Modules (import/export)
      - Enhanced object literals
