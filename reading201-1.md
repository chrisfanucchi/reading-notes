# Reading: Class 1 - Intro to the Web, HTML amd Javascript

## Introduction

Understanding how the web works and its related protocols and applicable languages is important to know for a software developer hoping to focus in web development.

## The Web, Web Design & JavaScript Basics

1. Compose a short poem describing how HTTP sends data between computers.

   HTTP is a protocol you see
   Making it possible for messages to travel from server A to server B
   It starts with a DNS lookup, and a handshake of course
   Then the message is broken up and reassembled in the browser, as pretty as can be

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

   Parsing, in relation to browsers, is the process of taking the raw data from the packets received over the network and turning the markup tags and scripts, from HTML, CSS and JavaScript files, into a functioning document object model (aka a web page).

   - HTML is parsed first
   - Requests are made of the server for any files mentioned in \<link> or \<script> elements
   - A document object model (DOM) and CSS object (CSSOM) model are generated in memory, as any JavaScript is compiled and executed
   - As the DOM is built, the CSSSOM is applied, and the JavaScript is executed, the browser presents the page content to the screen

3. How can you find images to add to a Website?

   Google searches for open source images can be helpful, or even purchasing images online. It is important to know and understand the licensing surrounding any image you use on a website.

4. How do you create a String vs a Number in JavaScript?

   When declaring a variable, a string is created by putting the value in single or double quotes, and a number is created by using a number without quotes around it.

5. What is a Variable and why are they important in JavaScript?

   Variables hold values that can be used throughout a program, allowing the reuse or saving of a value, for use later in the program.

## Introduction to HTML

1. What is an HTML attribute?

   An HMTL attribute is information that is placed with an elements brackets that provide additional information about the element, such as a file location, ID, or an assignment to a class. The attribute is not displayed to the user.

2. Describe the Anatomy of an HTML element.

   An HTML element is enclosed in greater than and less than brackets. It contains the name of the tag and possibly attributes. Most elements have an opening and closing tag, with content in between that may be displayed to the user. Some tags to not need a closing tag. However, in those cases, it is appropriate to include a forward slash just before the closing bracket.

3. What is the Difference between \<article> and \<section> element tags?

   A Section element is used to create a generic standalone section of a web page, which can be handy for things such as making styling changes to everything in that part of the web page. An Article element is used to create a self-contained composition on web page that might be distributable or reusable, such as a news article or forum post.

4. What Elements does a “typical” website include?

   A typical (minimalist) website would include the elements: html, head, body, header, main, footer, p, a h1-6, and likely, nav, section, div, span, and ul/li as well.

5. How does metadata influence Search Engine Optimization?

   Search engines can interrogate the data in the meta tags to acquire more information about the page’s content.

6. How is the \<meta> HTML tag used when specifying metadata?

   The meta tag indicated to the browser that the data in the tag is being used to describe things about the page, to include more information about the content on the page or what typeset should be used.

## How to start to design a Website

1. What is the first step to designing a Website?

   Define the object and intent for the website.

2. What is the most important question to answer when designing a Website?

   What exactly do I want to accomplish? [^1]

## Semantics

1. Why should you use an \<h1> element over a \<span> element to display a top level heading?

   One primary reason is that the h1 tag lets search engines now that the content between the h1 tags is the main header and likely includes words of value would influence the page’s ranking. It can also help future developers when proper semantics are used.

2. What are the benefits of using semantic tags in our HTML?

   It helps search engines better assess the content and intent of the web page, for more accurate search results and page rankings, as well as help the developer and future developers understand the intent and use of the parts of the page.

## What is JavaScript?

1. Describe 2 things that require JavaScript in the Browser?

   - Using APIs on a web page
   - Dynamically modifing HTML and CSS on the fly

2. How can you add JavaScript to an HTML document?

   You can add it in line with the HTML or using an external file with a \<script>.

## Things I want to know more about

I’m actually pretty good for right now.

---

[^1]: “How do I start to design my website?”, [https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)
