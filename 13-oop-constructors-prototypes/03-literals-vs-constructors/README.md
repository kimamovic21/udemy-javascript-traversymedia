# 03 - Literals vs Constructors

This lesson compares primitive literals with constructor-created wrapper objects.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the literal and constructor comparisons.

## What This Covers

- Comparing string literals with `new String()`.
- Understanding primitive boxing.
- Reading primitive values from wrapper objects with `valueOf()`.
- Checking constructors and `instanceof`.
- Comparing number and boolean literals with constructor objects.
- Comparing array literals with `new Array()`.
- Creating functions with literals and the `Function` constructor.
- Comparing object literals with `new Object()`.

## Things To Notice

Primitive literals can still use methods because JavaScript temporarily wraps them behind the scenes. That does not make the primitive itself an instance of the wrapper constructor.
