# 04 - Block Scope

This lesson explains block scope and compares `const`, `let`, and `var` inside blocks and functions.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains block scope examples.

## What This Covers

- Blocks created by `if` statements.
- Blocks created by loops.
- `const` and `let` being block scoped.
- `var` not being block scoped.
- `var` still being function scoped.
- How top-level `var` can become a property on the browser `window` object.

## Things To Notice

The commented `console.log(y)` and `console.log(i)` lines would throw because those variables were declared inside blocks. The `var c` example behaves differently because `var` does not follow block scope.
