# 07 - Promises

This lesson introduces JavaScript promises for representing asynchronous work that can resolve or reject later.

## Files

- `index.html` loads the promise demo page and includes `script.js`.
- `script.js` contains the promise creation and consumption examples.

## What This Covers

- Creating a new `Promise`.
- Simulating async work with `setTimeout()`.
- Resolving a promise with `resolve()`.
- Rejecting a promise with `reject()`.
- Consuming resolved data with `.then()`.
- Handling errors with `.catch()`.
- Running cleanup-style code with `.finally()`.
- Seeing asynchronous code run after global synchronous code.

## Things To Notice

The `getUser` example currently sets `error` to `true`, so the promise rejects and the `.catch()` handler runs.
