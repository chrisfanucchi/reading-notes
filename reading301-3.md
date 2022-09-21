# Reading: Class 3 - Passing Functions as Props

## Lists and Keys

1. What does .map() return?

   This method creates a new array by calling a function and iterating through every element in the calling array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

   The following is one possibility, using JSX in React:

   ```jsx
   array.map(value => <p>value</p>);
   ```

3. Each list item needs a unique \_\_\_\_.

   Key

4. What is the purpose of a key?

   Keys help React identify any changes to similar elements.

## The Spread Operator

1. What is the spread operator?

   It makes it possible to quickly copy all or part of an existing array or object into another object. The operator itself is three dots (...).

2. List 4 things that the spread operator can do.

   - Copying an array
   - Adding to state in React
   - Combining objects
   - Using an array as arguments

3. Give an example of using the spread operator to combine two arrays.

   ```js
   newArray = [...arrayOne, ...arrayTwo];
   ```

4. Give an example of using the spread operator to add a new item to an array.

   ```js
   let numbers = [1, 2, 3, 4];
   numbers = [9, ...numbers];
   // numbers = [9, 1, 2, 3, 4]
   ```

5. Give an example of using the spread operator to combine two objects into one.

   ```js
   let objOne = { name: 'bob' };
   let objTwo = { id: 12 };
   let newObject = { ...objOne, ...objTwo };
   // newObject = { name: 'bob', id: 12 }
   ```

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

   Create a function that would be passed to the child component.

2. In your own words, what does the increment function do?

   In the video, the increment function in the parent component takes an argument passed by the child, finds that value in an array of objects, and increments a number value for tha specif name found.

3. How can you pass a method from a parent component into a child component?

   Pass the method as a prop to the child component (e.g. increment = {this.increment}).

4. How does the child component invoke a method that was passed to it from a parent component?

   It can be invoked using _this.props.methodName_.

## Things I want to know more about

I'm curious if there are any limitation to the passing of functions to child components.
