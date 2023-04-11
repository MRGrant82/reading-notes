# React Component Lifecycle Events

Here are the different lifecycle events that React components go through:

- **Mounting phase**
  - `constructor()`: Called when a component is first created. Used for initializing state and binding event handlers.
  - `static getDerivedStateFromProps()`: A static method that is called when the component is first created and whenever props change.
  - `render()`: Called to render the component's UI.
  - `componentDidMount()`: Called when the component is first mounted to the DOM.

- **Updating phase**
  - `static getDerivedStateFromProps()`: A static method that is called when the component's props change.
  - `shouldComponentUpdate()`: Called before the component is re-rendered to determine if the re-render is necessary.
  - `render()`: Called to render the component's UI.
  - `getSnapshotBeforeUpdate()`: Called right before changes from the virtual DOM are actually reflected in the DOM.
  - `componentDidUpdate()`: Called after the component's updates are flushed to the DOM.

- **Unmounting phase**
  - `componentWillUnmount()`: Called just before a component is unmounted and destroyed. Used for cleanup tasks like removing event listeners and canceling network requests.

- **Error handling phase**
  - `static getDerivedStateFromError()`: A static method that is called when a child component throws an error.
  - `componentDidCatch()`: Called after a child component throws an error.


# React Component Lifecycle

- Based on the diagram, 'constructor' happens first, then 'render', then 'componentDidMount'.
- The very first thing to happen is the creation of the component's class object.
- The correct order of lifecycle events is: constructor, render, componentDidMount, React Updates, componentWillUnmount.
- componentDidMount is called immediately after a component is mounted to the DOM, and is used for tasks that require access to the DOM like setting up event listeners or fetching data from a remote API.


# Props in JavaScript from Video

- Types of things you can pass: Any value or object.
- Difference from state: Props are passed from parent to child, state is internal.
- When to re-render: When state or props change.
- Examples of state: Input values, logged in status, data fetching.

