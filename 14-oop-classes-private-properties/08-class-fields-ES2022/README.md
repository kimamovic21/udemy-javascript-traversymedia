# 08 - Class Fields ES2022

This lesson introduces modern class fields and true private properties and methods with the `#` syntax.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the ES2022 private field wallet example.

## What This Covers

- Defining private class fields with `#`.
- Defining private class methods with `#`.
- Updating private state from public methods.
- Preventing invalid withdrawals.
- Exposing private values with getters.
- Comparing true private fields with underscore conventions.

## Things To Notice

Private fields like `#balance` cannot be read or changed from outside the class. The public getter controls how outside code can view the value.
