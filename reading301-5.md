# Reading: Class 5 - Putting It All Together

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?

   The principle states that a component should only do one thing. Functions, UI's and other similar items should be broken up into components that only do or represent one type of thing/activity, and possibly that matches one piece of the data model.

2. What does it mean to build a ‘static’ version of your application?

   A static version of an application is one where there is no "interactivity" written into the code. It simply consists of the various component (without state) needed to enact the data model.

3. Once you have a static application, what do you need to add?

   Next interactivity is added, using state.

4. What are the three questions you can ask to determine if something is state?

   > - Is it passed in from a parent via props? If so, it probably isn’t state.
   > - Does it remain unchanged over time? If so, it probably isn’t state.
   > - Can you compute it based on any other state or props in your component? If so, it isn’t state.[^1]

5. How can you identify where state needs to live?

   The owner of state show be either the component that needs the state or the highest parent, in common, between child components that need the state.

## Higher-Order Functions

1. What is a “higher-order function”?

   Higher-order functions are functions that either take other functions as arguments or return them.

2. Explore the _greaterThan_ function as defined in the reading. In your own words, what is line 2 of this function doing?

   Line 2 is an arrow function that returns a boolean response, when invoking a function that was created by the greaterThan function, whose answer comes from a comparison between the current provided argument and an argument provided when the greaterThan function was previously used to create the new function.

3. Explain how either _map_ or _reduce_ operates, with regards to higher-order functions.

   A function is passed as an argument to the _map_ or _reduce_ methods that creates an altered version of the array by applying the passed function to each object in the primary array.

## Things I want to know more about

I think I need to spend a little more time playing with the _reduce_ method.

---

[^1]: _Thinking in React_, Retrieved September 22, 2022, from [https://reactjs.org/docs/thinking-in-react.html](https://reactjs.org/docs/thinking-in-react.html)
