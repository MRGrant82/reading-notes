Forms

In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

Controlled Components

In React, a component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a "controlled component".

<input type="text" value={this.state.value} onChange={this.handleChange} />

Handling Multiple Inputs

When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

<textarea name="essay" value={this.state.essay} onChange={this.handleChange} />

<select name="flavor" value={this.state.flavor} onChange={this.handleChange}>
  <option value="grapefruit">Grapefruit</option>
  <option value="lime">Lime</option>
  <option value="coconut">Coconut</option>
  <option value="mango">Mango</option>
</select>

File Input Tag

In HTML, an <input type="file"> lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API. In React, an <input type="file" /> is always an uncontrolled component because its value can only be set by a user, and not programmatically.

Handling Multiple Files

If you ever need to access more than one file, use the multiple attribute:

<input type="file" multiple={true} />

The FileList Object

When working with files, you often need to access the file name, file size, and file type. Here's an example showing how to extract the file name from a FileList object, which is returned by the HTML file input field.

const file = e.target.files[0];
console.log(file.name);

# JavaScript: The Conditional Ternary Operator Explained

The ternary operator is a concise way to write simple if statements in JavaScript. It takes three operands:

condition ? expressionIfTrue : expressionIfFalse

If the condition is true, the first expression is evaluated, and the second expression is evaluated if the condition is false.

For example:

const x = 10;
const y = 5;

const isGreater = x > y ? true : false;
console.log(isGreater); // true

We can also nest ternary operators:

const num = 8;

const isPositive = num > 0 ? true : num < 0 ? false : 'zero';
console.log(isPositive); // true

This is equivalent to:

let isPositive;
if (num > 0) {
  isPositive = true;
} else if (num < 0) {
  isPositive = false;
} else {
  isPositive = 'zero';
}

While the ternary operator can make code more concise, it can also make it less readable. Use it judiciously.
# React Bootstrap Forms Overview

React Bootstrap provides a set of form components that are compatible with standard HTML form controls.

The `Form` component is the top-level component for all forms in React Bootstrap. It provides a few helpful props such as `onSubmit` and `validated`.

Other form components include:
- `Form.Group`: a container for a label and form control
- `Form.Control`: an HTML form control such as an input, textarea, or select
- `Form.Check`: a set of radio buttons or checkboxes
- `Form.Label`: a label for an HTML form control

React Bootstrap forms can also be extended with additional functionality using `react-hook-form`, a lightweight library for form validation and management.

Overall, React Bootstrap forms provide a flexible and easy-to-use way to create and manage forms in your React applications.
# React Conditional Rendering

- React components can be conditionally rendered based on a certain condition or state.

- Conditional rendering can be done using conditional statements, ternary operators or short-circuit evaluation.

- `if` statements cannot be used inside JSX as they are not expressions.

- The ternary operator `condition ? true : false` can be used in JSX to conditionally render elements.

- Short-circuit evaluation can be used to conditionally render elements based on a logical AND (`&&`) or a logical OR (`||`) condition.

- Conditional rendering can also be achieved using component state or props.

- In React, conditional rendering can help optimize the performance of your application by avoiding unnecessary re-renders.

