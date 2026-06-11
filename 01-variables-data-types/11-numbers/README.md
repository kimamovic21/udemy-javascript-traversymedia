# 11 - Working With Numbers

This lesson introduces number objects, number formatting methods, and useful static properties on the `Number` object.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` experiments with methods on a number object and logs the final result.

## What This Covers

- Creating a number object with `new Number()`.
- Converting numbers to strings with `.toString()`.
- Formatting decimals with `.toFixed()`.
- Controlling significant digits with `.toPrecision()`.
- Using exponential notation with `.toExponential()`.
- Formatting for a locale with `.toLocaleString()`.
- Getting the primitive value with `.valueOf()`.
- Inspecting `Number.MAX_VALUE` and `Number.MIN_VALUE`.

## Things To Notice

Several formatting methods return strings, not numbers. Check `typeof` while experimenting if you want to see which methods change the type.
