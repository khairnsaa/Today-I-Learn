# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

## React Class Component vs Functional Component

### Class Component
1. class component requires you to extend from React.
2. It must have the render() method returning JSX
3. Also known as Stateful components because they implement logic and state.
4. React lifecycle methods can be used inside class components (for example, componentDidMount).

### Functional Component
1. A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element
2. There is no render method used in functional components.
3. Also known as Stateless components as they simply accept data and display them in some form, that they are mainly responsible for rendering UI.
4. React lifecycle methods (for example, componentDidMount) cannot be used in functional components.
