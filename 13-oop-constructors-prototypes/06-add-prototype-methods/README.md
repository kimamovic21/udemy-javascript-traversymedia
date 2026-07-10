# 06 - Add Prototype Methods

This lesson moves shared methods onto a constructor's prototype so every instance can reuse them.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the prototype method examples.

## What This Covers

- Creating a constructor with instance properties.
- Adding methods to `Rectangle.prototype`.
- Calculating area and perimeter from prototype methods.
- Checking whether a rectangle is a square.
- Updating instance data from a prototype method.
- Reusing shared behavior across multiple instances.

## Things To Notice

Prototype methods are shared instead of copied onto every object instance. That is more efficient when many objects need the same behavior.
