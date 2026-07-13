# 04 - Bind This

This lesson shows how `bind()` keeps the correct `this` value when passing a class method as an event handler.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the `this` binding example.

## What This Covers

- Creating a class that wires up a DOM event.
- Passing a class method to `addEventListener()`.
- Understanding how event handlers change `this`.
- Using `.bind(this)` to preserve the instance context.
- Logging the class instance from an event handler.

## Things To Notice

Without `.bind(this)`, the button would become the `this` value inside `getServerName()`. Binding keeps `this` pointed at the `App` instance.
