# 09 - Flags Descriptors

This lesson explores property descriptors and the flags that control how object properties behave.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the property descriptor examples.

## What This Covers

- Reading a built-in property descriptor.
- Understanding `writable`, `configurable`, and `enumerable`.
- Defining property flags with `Object.defineProperty()`.
- Preventing property value changes.
- Preventing property deletion.
- Hiding a property from enumeration.
- Reading descriptors with `Object.getOwnPropertyDescriptor()` and `Object.getOwnPropertyDescriptors()`.

## Things To Notice

After `name` is made non-enumerable, it no longer appears in `Object.entries()`, even though the property still exists on the object.
