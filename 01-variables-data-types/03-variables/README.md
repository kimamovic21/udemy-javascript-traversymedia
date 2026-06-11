# 03 - Variables

This lesson introduces variables and explains the practical differences between `let`, `const`, and older `var` declarations.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains examples of declaring, assigning, reassigning, and logging variables.

## What This Covers

- Creating variables with `let` and `const`.
- Reassigning values with `let`.
- Why `const` variables cannot be reassigned.
- Mutating arrays and objects stored in `const` variables.
- Basic variable naming rules and naming styles.
- Declaring variables without an immediate value.
- Declaring multiple variables in one statement.

## Things To Notice

`const` prevents rebinding the variable name, but it does not freeze an object or array. That is why the lesson can still push into `arr` and update properties on `person`.
