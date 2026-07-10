# 05 - Prototypes

This lesson introduces the prototype chain and shows where inherited object methods come from.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the prototype inspection examples.

## What This Covers

- Creating constructor-based instances.
- Calling inherited methods like `toString()`.
- Understanding that constructor prototypes inherit from `Object.prototype`.
- Inspecting an object's prototype with `Object.getPrototypeOf()`.

## Things To Notice

The `Rectangle` instance can use methods it did not define directly because JavaScript looks up the prototype chain.
