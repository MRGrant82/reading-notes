# Domain Modeling

## What is domain modeling?

- Domain modeling is the process of creating a conceptual model in code for a specific problem domain. 
- It describes the various entities, their attributes, and the behaviors they have in relation to each other.

## How to create a domain model?

- Identify the entities relevant to the problem domain.
- Define the attributes and behaviors of each entity.
- Identify the relationships between entities.
- Use object-oriented programming to create a conceptual model of the problem domain.

## Why is domain modeling important?

- It helps to create a shared understanding of the problem domain.
- It provides a blueprint for designing and building software solutions.
- It helps to identify potential problems and edge cases.

## Tips for domain modeling

- Start with a simple model and iterate as needed.
- Use clear and concise names for entities, attributes, and behaviors.
- Focus on the problem domain, not the implementation details.
- Test the model with sample data to ensure it meets the requirements.

# HTML tables - basics

## What is an HTML table?

- An HTML table is a way of organizing and displaying data in rows and columns.
- It consists of one or more rows, each containing one or more cells.
- A cell can contain text, images, links, or other HTML elements.

## How to create an HTML table?

- Use the `<table>` element to create a table.
- Use the `<tr>` element to create a row.
- Use the `<td>` element to create a cell.
- Use the `<th>` element to create a header cell.
- Use the `colspan` and `rowspan` attributes to merge cells.
- Use the `scope` attribute to specify the scope of a header cell.

## How to style an HTML table?

- Use CSS to style the table and its elements.
- Use the `border` property to add borders to cells and the table.
- Use the `background-color` property to add colors to cells and the table.
- Use the `text-align` property to align text within cells.
- Use the `font-weight` property to make header cells bold.

# JavaScript objects - basics: Introducing constructors

## What is a constructor?

- A constructor is a function used to create objects.
- It is called with the `new` keyword and returns a new object.
- The properties and methods of the object are defined in the constructor function.

## How to create a constructor?

- Define a function with the properties and methods for the object.
- Use the `this` keyword to refer to the object being created.
- Use the `new` keyword to create a new object from the constructor.

## How to add properties and methods to an object?

- Use dot notation or bracket notation to add properties and methods to an object.
- Use the `this` keyword to refer to the object inside the constructor or method.

## How to create multiple objects with the same properties and methods?

- Use a constructor to create multiple objects with the same properties and methods.
- Use the `new` keyword to create a new object from the constructor.

# A Beginner's Guide to JavaScript's Prototype

## What is a prototype?

- A prototype is an object from which other objects inherit properties and methods.
- It is a template or blueprint

Q: Explain why we need domain modeling.
A: To create a shared understanding, provide a blueprint for software solutions, and identify potential problems and edge cases.

Q: Why should tables not be used for page layouts?
A: They make code more difficult to read, modify, and maintain and do not provide the same level of flexibility and accessibility as using CSS for layout.

Q: List and describe 3 different semantic HTML elements used in an HTML <table>.
A: <thead> - groups header content, <tbody> - groups body content, <tfoot> - groups footer content.

Q: What is a constructor and what are some advantages to using it?
A: A function used to create objects in JavaScript. Advantages include creating multiple objects with the same properties and methods and making code more organized and easier to maintain.

Q: How does the term "this" differ when used in an object literal versus when used in a constructor?
A: In an object literal, "this" refers to the object that contains the function or property. In a constructor, "this" refers to the object being created.

Q: Explain prototypes and inheritance via an analogy from your previous work experience.
A: Prototypes are like templates used in construction to build multiple houses with the same design. Inheritance is like passing down traits from a parent to a child.

Q: Explain prototypes and inheritance via an analogy from your previous work experience.
A: We had a specific format that we were required to use for some of our products (prototype) and we passed down the knowledge of how to do this specific format to all subordinate analysts. (inheritence)
