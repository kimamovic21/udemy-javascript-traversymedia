# 03 - Global and Function Scope

This lesson demonstrates where variables can be accessed from global code, functions, and blocks.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains global scope and function scope examples.

## What This Covers

- Browser globals such as `window`.
- Creating a global variable.
- Accessing global variables inside functions.
- Accessing global variables inside blocks.
- Variable shadowing with a local variable that has the same name as a global variable.
- Function-scoped variables.
- What happens when code tries to access a variable outside its scope.

## Things To Notice

The `console.log(y)` line is intentionally placed outside the function where `y` is created. Running it demonstrates that function-scoped variables are not available globally.
