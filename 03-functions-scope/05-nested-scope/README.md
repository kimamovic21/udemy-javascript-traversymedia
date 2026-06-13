# 05 - Nested Scope

This lesson shows how scope works when functions or blocks are placed inside other functions or blocks.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains nested function and nested block examples.

## What This Covers

- Creating a function inside another function.
- Inner functions accessing variables from outer functions.
- Outer functions not accessing variables declared inside inner functions.
- Nested `if` blocks.
- Inner blocks accessing values from outer blocks.
- Scope errors when code tries to access an inner variable from outside its block.

## Things To Notice

The inner `second()` function can use `x` from `first()`, but `first()` cannot use `y` from `second()`. Scope works from the inside outward, not the other way around.
