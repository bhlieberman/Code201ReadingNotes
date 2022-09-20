# React Lifecycle

1. A component is rendered before `componentDidMount` is called.
2. Mounting is the first phase of a React component's lifecycle.
3. `constructor` -> `render` -> `componentDidMount` -> `React updates` -> `componentWillUnmount`
4. `componentDidMount` is called after a React component mounts and it can be used to make network requests etc. for the content of a component

# React state vs props

1. Props can be values like strings or numbers that represent data your application will display. They are like arguments to a function.
2. State is internal to a component. It is the representation of a component's identity at a discrete moment in time. It must be updated inside the component itself. Props on the other hand must be updated externally by the parent component.
3. Components are re-rendered when their state changes.
4. State could be used to track a counter or form data that changes as the user interacts with the app.