1. What does .map() return?
It returns a new array with each element transformed by a callback function.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
Use .map() to loop through the array and return a JSX element for each value.

3. Each list item needs a unique ____.
Key

4. What is the purpose of a key?
To help React identify which items have changed, added, or removed in a list.

5. What is the spread operator?
JavaScript syntax that allows an iterable to expand in place.

6. List 4 things that the spread operator can do.
Copy/concatenate arrays, copy/merge objects.

7. Give an example of using the spread operator to combine two arrays.
const combinedArray = [...array1, ...array2];

8. Give an example of using the spread operator to add a new item to an array.
const newArray = [...originalArray, 4];

9. Give an example of using the spread operator to combine two objects into one.
const combinedObject = {...object1, ...object2};

10. In the video, what is the first step that the developer does to pass functions between components?
Define a function in the parent component.

11. In your own words, what does the increment function do?
Increases the value of a count by one.

12. How can you pass a method from a parent component into a child component?
Pass the method as a prop to the child component.

13. How does the child component invoke a method that was passed to it from a parent component?
The child component can invoke the method by calling it using props.

- Lists are a common way to display items in a dynamic UI.
- Keys help React identify which items have changed, added, or removed.
- A good key is a unique string that stays the same across renders.
- Keys should be given to the elements inside the array, not the array itself.
- Using the index of the array as a key can cause issues with reordering.
- Keys should be stable, predictable, and unique among siblings.
- The spread operator is JavaScript syntax that allows an iterable to expand in place.
- It can be used to copy an array, concatenate two or more arrays, copy an object, and merge two or more objects.
- The spread operator can also be used with function arguments and with the rest parameter syntax.
- The spread operator provides a concise and flexible way to manipulate data structures.
- Lifting state up is the process of moving state from a child component to its parent component.
- This allows multiple components to share the same data and stay in sync.
- State should be lifted up to the lowest common ancestor that needs it.
- Data should be passed down to child components via props.
- Lifting state up can simplify the code and reduce bugs caused by inconsistent state.

