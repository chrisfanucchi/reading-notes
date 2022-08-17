# Reading: Class 3 - HTML Lists, Control Flow with JS, and the CSS Box Model

## Ordered and Unordered lists

1. When should you use an unordered list in your HTML document?

   A \<ul> (unordered list) should be used when the order of the tiems in the list has not mean (i.e. they have no priority or number to thwm).

2. How do you change the bullet style of unordered list items?

   Using the CSS _type_ attribute, which has the values circle, disc, and square.

3. When should you use an ordered list vs an unorder list in your HTML document?

   The \<ol> (ordered list) should be used when the order of the items in the list is meanful, otherwise the \<ul> (unorderlist) should be used.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

- Using the _start="x"_ attribrute, to set the starting number to x
- Using the _type_ attribute, to change the number to a letter or roamn numeral
- Also, using the _reversed_ attribute, to reverse the order of the count

## CSS - The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

   Padding and Margin live outside and all around Content. Padding is Contents closes neighbor, surrounding content on all sides. Margin lives outside of Padding and surrounds Padding all the way around. There is a fence between Padding and Margin's territory called the Border. As Margin and Padding adjust their top, right, bottom and left territory, the content and the items around Margin's territory will be displayed in different places and possibly arranged differently.

2. List and describe the four parts of an HTML elements box as referred to by the box model.

- Content Box - where your content is displayed
- Padding Box - sits around the content as white space
- Border Box - wraps the content and any padding
- Margin Box - wraps all the above boxes as whitespace, between it all and other elements on the page

## JS - Arrays, Operators and Expressions, Conditionals, Loops

1. What data types can you store inside of an Array?

   Arrays can store trings, numbers, objects, and other arrays.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

Yes, values from an array that are stored in an array can be accessed by using addition brackets that contact the index of the value desire. For example, 'Smith' can be retrieved using: people[1][0].

```js
const people = [
  ['pete', 32, 'librarian', null],
  ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'],
  ['bill', null, 'artist', null],
];
```

3. List five shorthand operators for assignment in javascript and describe what they do.

- 'x += y' - Adds y to x and placed the result in x
- 'x \*= y' - Multiplies y and x and places the result in x
- 'x /= y' - Divides x by y and places the result in x
- 'x &= y' - Performd a logical AND operation on x and y, and places the result in x
- 'X++' - Increments x by 1 (equivalent of x = x + 1)

4. Read the code below and evaluate the last expression and explain what the result would be and why.

- The resulting value would be the string: '10dog'
- When being concatenated with a string, the 10 becomes a string and is combined with 'dog' and the false is dropped.

```js
let a = 10;
let b = 'dog';
let c = false;

// evaluate this
a + c + b;
```

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

A conditional statement could be used to evaluate input from a user and branch the program according to the answer.

6. Give an example of when a Loop is useful in JavaScript.

A loop can be used to loop enough times to interact with every value stored in an array, and do something with each one.
