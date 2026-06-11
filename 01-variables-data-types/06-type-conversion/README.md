# 06 - Type Conversion

This lesson shows explicit ways to convert values from one JavaScript type to another.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` experiments with converting a value named `amount`.

## What This Covers

- Converting strings to numbers with `parseInt()`, unary `+`, and `Number()`.
- Converting numbers to strings with `.toString()` and `String()`.
- Converting strings to decimals with `parseFloat()`.
- Converting values to booleans with `Boolean()`.
- Common ways to produce `NaN`.
- Checking the result with `typeof`.

## Things To Notice

The starting value is `"hello"`, so many numeric conversions result in `NaN`. This is useful because it shows what happens when JavaScript cannot create a valid number from a value.
