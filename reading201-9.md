# Reading: Class 9 - HTML Forms and JS Events

## HTML Forms

1. Why are forms so important in web development?

   Forms allow the user to input data/information for processing by the page/server.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

   - Create a quick mockup of the form to help define the right set of data and get user feedback
   - Keep forms small and manageable, from the user's perspective

3. List 5 form elements and explain their importance.

   - \<fieldset> - Used to group widgets together for styling and semantics
   - \<label> - Defines a label for a form widget
   - \<input> - Create an area for user input and can be defined for later use
   - \<button> - Gives users a object to interact with that can be listened and raacted to by scripting
   - \<select>\<option> - Create a set of options (displayed like a dropdown box) that a user can select from and the selection later used by the page or scripting

## Intro to JS Events

1. How would you describe events to a non-technical friend?

   Events are things that happen on a webpage, either automatically or through user interaction, that can be detected or listened for and responded to by a program.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

   - The name of the event
   - A function to handle the event

3. Describe the event object. Why is the target within the event object useful?

   An event object is what is passed to event handlers to provide extra features and information. The target property refers to the element that the event occured in.

4. What is the difference between event bubbling and event capturing?

   - Bubbling is when an event is fires and "bubbles" its way up through each of the parent elements that also triggered, and only occurs if _bubbles_ is true
   - Event capturing is the first phase of the event firing process, in which the browser starts with the outmost element and works its way in, to see if any ancestor also fired

## Things I want to know more about

I need to read more about event capturing.
