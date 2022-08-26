# Reading: Class 10 - Debugging

## Troubleshooting JavaScript

1. Name some key differences between a Syntax Error and a Logic Error.

   - Syntax Errors include spelling errors, and other simple typos
   - Logic errors occur when there isn’t a problem with syntax, but the wrong instruction are being given or you are not getting the expected result 

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

   - I was getting an error in the console indicating that there wasn’t a certain HTML element on the current page. It was because I was on my index page, which did not have the button that was being listen for. I wrong an if/else statement that check what page was currently being viewed and only ran the effected functions/listeners on the pages that had them. This was a logic error.
   - When a user enters a store name with a space in it, the console displayed an error indicating that spaces could not be in element names, since I use the store name as an element ID. I wrote a quick validation if/else statement that stopped the program from continuing and popped up an alert box to the user, if the Store Name entered could not be a valid element name. This was a logic error.

3. How will this topic continue to influence your long term goals?

   As an experienced programmer, I know that all coding involves debugging, no matter how good you think you are.

## The JavaScript Debugger

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

   The JavaScript Debugger allows you to step through your program, line by line, or set stopping points within the code, to see the state of things at each step of the way or at a certain moment in the program’s time.

2. Define what a breakpoint is.

   A breakpoint is a programmer selected point in the program that the program will halt to allow for analyzing the state and status of the various parts of the program.

3. What is the call stack?

   The Call Stack window in a debugger shows what code was being executed in a given snapshot or breakpoint.

## Things I want to know more about

I'm interested in the various debugger available today.
