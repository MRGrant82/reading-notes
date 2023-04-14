### Notes on "Thinking in React"

#### Step 1: Break the UI into a component hierarchy
- Start by breaking the UI into a component hierarchy of smaller, reusable parts.
- Single Responsibility Principle: Each component should ideally only do one thing.
- Use noun phrases to name your components, e.g. "ProductTable", "SearchBar", etc.
- Draw boxes around every component and subcomponent in the mock and give them names.

#### Step 2: Build a static version of the UI
- The static version of the UI will have no interactivity.
- It's a good idea to build the static version before adding interactivity because it helps you focus on just the UI.
- Use props to pass data from parent to child components.
- The static version should have a complete component hierarchy, but the components will not yet be reusable.

#### Step 3: Identify the minimal (but complete) representation of UI state
- Identify the absolute minimal representation of the state your UI needs.
- DRY (Don't Repeat Yourself): Keep as little state as possible in the components that need it.
- Figure out which component should own that state.
- In React, data flows down the component hierarchy through props.

#### Step 4: Identify where your state should live
- Identify which component or components own and control the state.
- Use React's one-way data flow to pass state down to child components.
- If a component needs to update the state, it should call a callback function passed down from the parent component.

#### Step 5: Add inverse data flow
- If a child component needs to update the state of a parent component, pass a callback function down from the parent as a prop.
- The child component can call this callback function and pass the new data up to the parent.
- The parent component can then update its state and re-render the child with the new props.

### Notes on "Higher-Order Functions"

- Higher-order functions are functions that operate on other functions.
- They can take functions as arguments and/or return functions as values.
- Examples of built-in higher-order functions in JavaScript include "map", "filter", and "reduce".
- Functions that create new functions are also higher-order functions.
- They can be used to abstract over actions, generalize code, and separate concerns.

#### Abstraction
- Higher-order functions can be used to abstract over actions.
- For example, a function that performs an operation on every element of an array can be abstracted into a higher-order function that takes the operation as an argument.
- This allows the function to be more flexible and reusable.

#### Generalization
- Higher-order functions can be used to generalize code.
- For example, a function that performs an operation on arrays can be abstracted into a higher-order function that takes any collection as an argument.
- This allows the function to be more versatile and applicable to a wider range of data structures.

#### Separation of Concerns
- Higher-order functions can be used to separate concerns.
- For example, a function that performs an operation on an array and logs the results can be abstracted into a higher-order function that performs the operation and another function that logs the results.
- This allows the functions to be more modular and easier to reason about.
