# 08 - IIFE

This lesson introduces IIFEs, which are Immediately Invoked Function Expressions.

## Files

- `index.html` loads the lesson page and includes both `otherscript.js` and `script.js`.
- `otherscript.js` creates a `user` variable and logs it.
- `script.js` contains IIFE examples.

## What This Covers

- Creating a function expression that runs immediately.
- Giving an IIFE its own scope.
- Avoiding name collisions between separate scripts.
- Passing arguments into an IIFE.
- Creating a named IIFE.
- Calling helper logic immediately when the page loads.

## Things To Notice

Both JavaScript files use a `user` variable name. The IIFE keeps the `user` inside `script.js` scoped to that function, which prevents it from colliding with `otherscript.js`.
