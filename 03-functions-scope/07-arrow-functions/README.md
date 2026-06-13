# 07 - Arrow Functions

This lesson introduces arrow function syntax and compares it with regular function syntax.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains arrow function examples.

## What This Covers

- Writing a normal function declaration.
- Writing arrow functions.
- Returning values explicitly with `return`.
- Using implicit returns.
- Omitting parentheses for a single parameter.
- Returning an object literal from an arrow function.
- Using arrow functions as callbacks.
- Comparing regular callback syntax with arrow callback syntax.

## Things To Notice

When an arrow function returns an object directly, the object needs parentheses: `() => ({ name: "Brad" })`. Without them, JavaScript treats the braces like a function body.
