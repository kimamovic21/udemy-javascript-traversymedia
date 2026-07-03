# 06 - Async Await

This lesson introduces `async` and `await` as a cleaner way to work with promises.

## Files

- `index.html` loads the async/await examples and includes `script.js`.
- `script.js` contains promise, fetch, and async function examples.

## What This Covers

- Creating a promise.
- Awaiting a promise inside an `async` function.
- Fetching users with `await`.
- Reading JSON with `await`.
- Writing async arrow functions.
- Returning promise rejections from async functions.
- Handling async errors with `.catch()`.

## Things To Notice

`await` can only be used inside an `async` function. The active `getPosts()` example throws an error so the final `.catch()` handler can receive it.
