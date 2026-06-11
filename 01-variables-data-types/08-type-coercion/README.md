# 08 - Type Coercion

This lesson demonstrates JavaScript's automatic type conversion, also called coercion.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` assigns different mixed-type expressions to `x` and logs the final result.

## What This Covers

- How `+` with a string can create string concatenation.
- How multiplication can coerce numeric strings into numbers.
- How `null`, `true`, and `false` behave when converted to numbers.
- Why `undefined` in numeric expressions commonly results in `NaN`.
- Using `Number()` when you want explicit conversion.

## Things To Notice

Coercion can be convenient, but it can also surprise you. This lesson is a good reason to prefer strict equality and explicit conversion when the expected type matters.
