# Reading: Class 2

## HTML Text Fundamentals - HTML Advanced Text Formatting

1. Why is it important to use semantic elements in our HTML?

   It is easier for developers to read and understand the intent of each part of a web page, as well as helping search engines better analyze the content for ranking purposes.

2. How many levels of headings are there in HTML?

   There are six levels of headings.

3. What are some uses for the \<sup> and \<sub> elements?

   These tags are used to denote superscript and subscript, respectively.

4. When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?

   The “title” attribute must be added.

## How CSS Is Structured

1. What are ways we can apply CSS to our HTML?

- Within the element using style=””
- In the HTML file, within its own block surrounded by \<style> \</style> tags
- By linking to an external CSS file using \<link rel="stylesheet" href="filename.css">

2. Why should we avoid using inline styles?

   It makes is harder to maintain and make changes, as well as the HTML harder to read for the developers.

3. Review the block of code below and answer the following questions:

- What is representing the selector?
  h2
- Which components are the CSS declarations?
  color: black, padding: 5px
- Which components are considered properties?
  color, padding

  ```CSS
  h2 {
  color: black;
  padding: 5px;
  }
  ```

## More JavaScript Basics

1. What data type is a sequence of text enclosed in single quote marks?

   A string

2. List 4 types of JavaScript operators.

   Arithmetic, relational, logical, equality.

3. Describe a real world problem you could solve with a Function.

   A function could be created that “shuffles” a virtual deck of cards for a poker program. This function could be invoked at various places in the program, whenever the cards need to be shuffled.

## Making Decisions In Your Code – Conditionals

1. An if statement checks a \_\_\_\_ and if it evaluates to \_\_\_\_, then the code block will execute.

   Condition, True.

2. What is the use of an else if?

   It is used to evaluate for additional conditions and executing a different block of code is true.

3. List 3 different types of comparison operators.

   Equal to, Strict Equal to, Greater than.

4. What is the difference between the logical operator && and \|\|?

   && - Chains two or more expressions together and when ALL are true, it returns true, else false
   \|\| - Chains two or more expressions together and when ANY are true, it returns true, else false
