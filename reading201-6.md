# Reading: Class 6 - Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

   An object is a container that holds named data and other smaller containers that can be access, added to and changed.

2. What are some advantages to creating object literals?

   The use of object literals makes it easy to see the data that is being palced into the object, in relatively clear human understandable language.

3. How do objects differ from arrays?

   > Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable. [^1]

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

   When you need to pass the property name as a variable, because it is being defined at runtime.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

   This refers to the object itself (in this case the obeject named _dog_) and it allows you to easily reference data from within the same object.

   ```js
   const dog = {
     name: 'Spot',
     age: 2,
     color: 'white with black spots',
     humanAge: function () {
       console.log(`${this.name} is ${this.age * 7} in human years`);
     },
   };
   ```

## Introduction To The DOM

6. What is the DOM?

   The DOM is the document object model, which is the data the makes up the structure and content of a web page.

7. Briefly describe the relationship between the DOM and JavaScript.

   The DOM is the visible, user accessible aspect of a web page, while Javascript is the programming language that control and/or manipulates the elements on the DOM (think of the DOM like a visit robot and Javascript as the brain of the robot).

## Things I want to know more about

I'd like to spend a little more time researching JS objects. I haven't had a lot of time playing with them in the past.

---

[^1]: "Objects vs. Arrays", https://medium.com/@zac_heisey/objects-vs-arrays-42601ff79421
