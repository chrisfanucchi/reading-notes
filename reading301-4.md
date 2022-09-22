# Reading: Class 4 - React and Forms

## React Docs - Forms

1. What is a ‘Controlled Component’?

   They are components that use their state to handle form data.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

   We should update it as soon as they enter them. It allows you to use what is input in real time on the form.

3. How do we target what the user is entering if we have an event handler on an input field?

   Using the value of _event.target.name_.

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

   It requires less writing and is an expression that returns a value.

2. Rewrite the following statement using a ternary statement:

   ```js
   if(x===y){
   console.log(true);
   ```

   Refactored:

   ```js
   console.log(x === y ? true : false);
   ```

## Things I want to know more about

I am eager to start trying forms in React!
