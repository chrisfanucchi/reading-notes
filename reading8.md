# Reading 8 – Operators and Loops

- An expression is a valid unit of code that resolves to a value, with two types of expressions:
  - Those that have side effects (such as assigning values)
  - Those that purely evaluate
- For Loop
  - for ([initialExpression]; [conditionExpression]; [incrementExpression])
    statement
- While Loop
  - while (condition)
    Statement

```javascript
// For Loop
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

// While Loop
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
```
