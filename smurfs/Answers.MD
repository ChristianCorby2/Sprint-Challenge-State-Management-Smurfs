1. What problem does the context API help solve?

Context enables the sharing of specific forms throughout all levels of your application. The specific problem is prop drilling

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

actions specify where to send data. reducers take the previous state of the action, and return the next state. Store is a way to use local storage in your code.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

Component State is stored locally within the Component. Application state is stored by your entire Application. So use application state for global modifications and use component state to edit sub components.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

redux-thunk is a middleware that returns a function instead of an action object. 

1. What is your favorite state management system you've learned and this sprint? Please explain why!

Context, It seems to be much easier, and removes the seemingly unnecessary steps of redux.