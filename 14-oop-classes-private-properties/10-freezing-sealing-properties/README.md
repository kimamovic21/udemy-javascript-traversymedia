# 10 - Freezing Sealing Properties

This lesson compares sealing and freezing objects to control whether properties can be added, removed, or changed.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the sealing and freezing examples.

## What This Covers

- Sealing an object with `Object.seal()`.
- Preventing property additions and removals.
- Changing values on a sealed object.
- Freezing an object with `Object.freeze()`.
- Preventing additions, removals, and value changes.
- Inspecting descriptors after sealing or freezing.
- Checking object state with `Object.isSealed()` and `Object.isFrozen()`.

## Things To Notice

A frozen object is also sealed. Sealed objects can still have existing writable values changed, but frozen objects cannot.
