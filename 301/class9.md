Functional programming: A programming paradigm that emphasizes the use of pure functions and immutable data structures.
Pure function: A function that always returns the same output for a given input, and has no side effects.
Benefits of pure functions: Easier to reason about, test, and debug. They are composable and can be combined to create more complex functions.
Immutability: The property of an object that cannot be changed after it is created.
Referential transparency: The property of a function that allows it to be replaced with its return value without changing the program's behavior.
Module: A file that contains a set of related functions, classes, or variables. It allows code to be organized into logical units and makes it easier to reuse code across multiple projects.
Require: A keyword in Node.js used to import modules. It loads the module into the current file and makes its contents available for use.
How to import a module in Node.js: Use the require() function to import the module.
How to make a module available: Export the module's functions, classes, or variables using the module.exports object.

### Concepts of Functional Programming in JavaScript

#### Pure functions
- Always return the same result for the same input.
- Do not produce side effects.

#### Immutability
- Data is never changed once created.
- Immutable data structures prevent accidental mutations.

#### Higher-order functions
- Functions that take other functions as arguments or return a function.
- Enables composition of smaller functions to build more complex ones.

#### Recursion
- A function that calls itself until a base case is reached.
- Useful for traversing data structures and solving problems.

#### Function composition
- Combining multiple functions to create a new one.

#### Currying
- A technique that converts a function with multiple arguments into a series of functions with one argument.
- Enables partial application and function composition.

#### Memoization
- Caching the results of a function to improve performance.
- Useful for expensive calculations that are repeated.
