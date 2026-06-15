# 05 - Truthy Falsy

This lesson explains how JavaScript treats values as truthy or falsy when they are used in conditional checks.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the truthy and falsy examples.

## What This Covers

- Identifying JavaScript's main falsy values.
- Understanding that most other values are truthy.
- Converting values to booleans with `Boolean()`.
- Handling `0` as a valid numeric value.
- Checking array length instead of checking the array directly.
- Checking object keys instead of checking the object directly.
- Comparing loose equality with strict equality.

## Things To Notice

Empty arrays and empty objects are truthy, so checking `.length` or `Object.keys().length` gives a better answer when you need to know whether they contain data.
