# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

## React Redux

There are 3 important things you need to know when using Redux. State, Action, reducer, and Store.

State is where you defined your variables

Action will be called when your components want something happened into the state

reducer is something that happened when the action is called. reducer will take the action, execute that single action on the old state and gives us back a new state. when we get back our new state, this state will be stored in state store

Store has one simple task, store our state

![image](https://user-images.githubusercontent.com/53510222/199052154-30d35dee-a039-4cfc-b6e5-6d47ac514b9d.png)

whenever the state is updated and therefore the new status is passed to the store. The store will automatically send it to the component who subscribe the store and the application (UI) will updated

![image](https://user-images.githubusercontent.com/53510222/199052282-688ad6ae-d556-4149-9593-983e2be2ecff.png)
