### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
  React is a JavaScript libray developed by facebook developers
  It is used to build/create fast user interfaces for websites and applications easier

- What is Babel?
  Babel is a JavaScript compiler that transforms the latest JS features into a compatible version of JS in current and older browsers/environment

- What is JSX?
  Stands for JavaScript XML, where you can write HTML in React

- How is a Component created in React?
  Create a JS file, import react, write your component code and export default the component to your App component

- What are some difference between state and props?
  Props are used to pass data from a parent component to a child component, they are also immutable and cannot be changed within a component
  State is mutable and can be updated using the "setState" function

- What does "downward data flow" refer to in React?
  Structure of a parent component does not get affected by modifications from the child components

- What is a controlled component?
  It is where a component is being controlled through a parent component. This can involve things like their state and behaviour
- What is an uncontrolled component?

- What is the purpose of the `key` prop when rendering a list of components?
  it is used to create a relationship between the component and the DOM element. The library uses this relationship to determine whether or not the component should be re-rendered

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
  Array are typically static, if the key is the index, reordering an item in the array changes it. Then React gets confused and can possible re-render the incorrect element

- Describe useEffect. What use cases is it used for in React components?
  Performs side effects on your components. Things like fetching data, updating the DOM, timers. This will get re render after the return

- What does useRef do? Does a change to a ref value cause a rerender of a component?
  Changing a ref does not trigger a re-render. You can store information between a re-render unlike regular variables which reset on every render

- When would you use a ref? When wouldn't you use one?
  Managing focus, text selection, or media playback

- What is a custom hook in React? When would you want to write one?
  Custom hooks can be a standalone component that can for example be a file to trigger a true or false (toggle) on a different function and can be reused in other components/files to reduce repeated code
