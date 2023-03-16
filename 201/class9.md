# Notes on Forms and JavaScript

## Forms

### [Learn/Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- HTML Forms are used to collect user input
- Forms consist of elements like input fields, select boxes, radio buttons, etc.
- Forms are submitted using the `submit` button or the `Enter` key
- Form data can be sent to a server for processing using various methods like `GET` and `POST`

### [Learn/Forms/Your_first_form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
- This tutorial teaches how to create a simple form with basic input fields
- Form elements like `input`, `label`, `select`, and `button` are covered
- The `method` and `action` attributes of the form tag are used to specify the submission method and destination respectively

### [Learn/Forms/How_to_structure_a_web_form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
- Best practices for structuring web forms are discussed
- Forms should be structured using `fieldset` and `legend` tags to group related input fields
- The `label` tag should always be used with input fields to make them more accessible to screen readers

### [Learn/Forms/HTML5_input_types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
- HTML5 introduced new input types like `email`, `url`, `date`, etc.
- These input types help to validate user input and provide a better user experience
- Other attributes like `required`, `min`, and `max` can also be used to validate input

## JavaScript

### [Learn/JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- JavaScript is a programming language used to create dynamic web content
- JavaScript can be used to manipulate HTML and CSS
- It can also be used to handle user events like clicks, keypresses, etc.
- JavaScript code can be embedded in HTML pages using the `script` tag

### [Learn/JavaScript/Building_blocks/Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- Events are actions or occurrences that happen in the browser, like a user clicking a button or a page finishing loading
- JavaScript can be used to respond to events and perform actions based on them
- The `addEventListener` method can be used to attach event listeners to HTML elements

### [Learn/Web/Events](https://developer.mozilla.org/en-US/docs/Web/Events)
- This page lists various events that can be used in JavaScript programming
- Events like `click`, `keydown`, `submit`, etc. are listed with their respective event objects
- Examples of how to use event listeners for different events are given


### Why are forms so important in web development?
Forms are a key way for users to interact with websites and provide data input.

### When designing a form, what are some key things to keep in mind when it comes to user experience?
Key things to consider include making the form easy to use, organizing it logically, using appropriate form elements, providing feedback, and designing for different devices.

### List 5 form elements and explain their importance.
- `input`: collects text, numbers, and data from users
- `label`: provides a description or name for an input field, making it accessible to screen readers
- `select`: creates drop-down menus with predefined options
- `radio buttons`: presents mutually exclusive options
- `textarea`: collects longer text inputs, such as comments or feedback

### How would you describe events to a non-technical friend?
Events are actions that happen in the browser when a user interacts with a website, such as clicking on buttons, typing in text fields, or scrolling the page.

### When using the addEventListener() method, what 2 arguments will you need to provide?
The type of event you want to listen for, and a function to execute when the event occurs.

### Describe the event object. Why is the target within the event object useful?
The event object contains information about an event that has occurred, including the type of event, the target element that triggered the event, and additional data. The target is useful for accessing the element that triggered the event.

### What is the difference between event bubbling and event capturing?
Event bubbling starts at the lowest level element and "bubbles up," while event capturing starts at the highest level element and "captures" the event as it propagates down to the lowest level element.
