# Coding Tip #27: Use Ternary Operator for Simple Conditions

The ternary operator is a shorter way of writing simple `if-else` statements, which can make your code more concise and readable.

**Tip**: Use ternary operators for simple conditions to reduce the length of your code.

Example:
```js
const age = 20;

// Bad: Using if-else
let message;
if (age >= 18) {
  message = 'Adult';
} else {
  message = 'Minor';
}

// Good: Using ternary operator
const message = age >= 18 ? 'Adult' : 'Minor';
```


---

Thanks!


🚀Keep Coding, Keep Growing!!
