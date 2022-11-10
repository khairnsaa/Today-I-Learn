# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

## React Hooks

React Hooks are simple JavaScript functions that we can use to isolate the reusable part from a functional component. Hooks can be stateful and can manage side-effects.  With React Hooks, we can isolate stateful logic and side-effects from a functional component. Hooks are JavaScript functions that manage the state's behaviour and side effects by isolating them from a component.

React provides a bunch of standard in-built hooks:
1. useState: To manage states. Returns a stateful value and an updater function to update it.
2. useEffect: To manage side-effects like API calls, subscriptions, timers, mutations, and more.
3. useContext: To return the current value for a context.
4. useReducer: A useState alternative to help with complex state management.
5. useCallback: It returns a memorized version of a callback to help a child component not re-render unnecessarily.
6. useMemo: It returns a memoized value that helps in performance optimizations.
7. useRef: It returns a ref object with a .current property. The ref object is mutable. It is mainly used to access a child component imperatively.

lease notice that each of these hook names start with use. it's a standard practice to identify a hook in the React codebase quickly. We can also create custom hooks for our unique use cases like data fetching, logging to disk, timers, and many more.
