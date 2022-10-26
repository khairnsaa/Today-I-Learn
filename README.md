# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

today i finished my personal task. creating todo list. i use react js as frontend framework. The React.js framework is an open-source JavaScript framework and library developed by Facebook. It’s used for building interactive user interfaces and web applications quickly and efficiently with significantly less code than you would with vanilla JavaScript. In React, you develop your applications by creating reusable components that you can think of as independent Lego blocks. These components are individual pieces of a final interface, which, when assembled, form the application’s entire user interface. React takes a different approach by letting you build what’s known as a single-page application (SPA). A single-page application loads only a single HTML document on the first request. Then, it updates the specific portion, content, or body of the webpage that needs updating using JavaScript.

## React Hooks

Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes. (We don’t recommend rewriting your existing components overnight but you can start using Hooks in the new ones if you’d like. Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. Hooks are:
1. Completely opt-in. You can try Hooks in a few components without rewriting any existing code. But you don’t have to learn or use Hooks right now if you don’t want to.
2. 100% backwards-compatible. Hooks don’t contain any breaking changes.
3. Available now. Hooks are now available with the release of v16.8.0.

With Hooks, you can extract stateful logic from a component so it can be tested independently and reused. Hooks allow you to reuse stateful logic without changing your component hierarchy. This makes it easy to share Hooks among many components or with the community

### When would I use a Hook? 
If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component. We’re going to do that right now!

so far in this bootcamp i learn about useState.

The useState() is a Hook that allows you to have state variables in functional components . so basically useState is the ability to encapsulate local state in a functional component. React has two types of components, one is class components which are ES6 classes that extend from React and the other is functional components. Class components a Component and can have state and lifecycle methods: class Message extends React. The  useState hook is a special function that takes the initial state as an argument and returns an array of two entries.  UseState encapsulate only singular value from the state, for multiple state need to have useState calls

```
const [state, setState] = useState(initialstate)
```
above is example how to use useState in react js
