# 03 - Array Nesting, Concat and Spread

This lesson shows how arrays can contain other arrays and how multiple arrays can be combined or flattened.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains examples of nested arrays, concatenation, spread syntax, and static array methods.

## What This Covers

- Nesting one array inside another.
- Reading values from nested arrays with multiple indexes.
- Combining arrays with `.concat()`.
- Combining arrays with the spread operator, `...`.
- Flattening nested arrays with `.flat()`.
- Checking if a value is an array with `Array.isArray()`.
- Creating arrays from array-like values with `Array.from()`.
- Creating arrays from individual values with `Array.of()`.

## Things To Notice

`fruits.push(berries)` places the whole `berries` array inside `fruits`. That is different from spreading values into a new array with `[...fruits, ...berries]`.
