# 06 - Function Declaration vs Expression

This lesson compares function declarations and function expressions.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains one function declaration and one function expression.

## What This Covers

- Creating a function declaration.
- Creating a function expression assigned to a variable.
- Returning values from both kinds of functions.
- Calling a function declaration before or after it appears in the file.
- Understanding why function expressions are not available before their assignment runs.

## Things To Notice

Function declarations are hoisted, so they can be called before the declaration in the source file. Function expressions stored in `const` are only usable after that line has executed.
