# Reading: Class 9 - Functional Programming

## Functional Programming Concepts

1. What is functional programming?

   It is functional programming is a programming paradigm where programs are constructed by applying and composing functions.[^1]

2. What is a pure function and how do we know if something is a pure function?

   A pure function will always return the same result for the same arguments, and it does not cause any observable side effects.

3. What are the benefits of a pure function?

   It is easier to test and produces predicable results.

4. What is immutability?

   Immutability means something can or will not change, such as the state of an object.

5. What is Referential transparency?

   A function is referentially transparent when is consistently yields the same result for the same argument provided.

## Node.JS - Modules and Require()

1. What is a module?

2. What does the word ‘require’ do?

   It imports access to another JavaScript module.

3. How do we bring another module into the file the we are working in?

   Using the require() statement.

4. What do we have to do to make a module available?

   Use _module.export = function_name_in_module_ in the imported module, and declare a variable in the calling module to the require statement, such as _const var_name = require('./imported_module_name')_.

## Things I want to know more about

When is it best to use sub-modules?

---

[^1]: _Functional programming_, Wikipedia, Retrieved on September 28, 2022, [https://en.wikipedia.org/wiki/Functional_programming](https://en.wikipedia.org/wiki/Functional_programming)
