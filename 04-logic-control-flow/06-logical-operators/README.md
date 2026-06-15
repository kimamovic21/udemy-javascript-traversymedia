# 06 - Logical Operators

This lesson covers logical operators and shows how they return values while evaluating conditions.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the logical operator examples.

## What This Covers

- Requiring every condition to be true with `&&`.
- Requiring at least one condition to be true with `||`.
- Understanding short-circuit evaluation.
- Returning the first falsy value or last value with `&&`.
- Returning the first truthy value or last value with `||`.
- Using `&&` to conditionally run a statement.
- Using the nullish coalescing operator `??`.

## Things To Notice

`??` only falls back when the left side is `null` or `undefined`, so values like `0` and an empty string stay as they are.
