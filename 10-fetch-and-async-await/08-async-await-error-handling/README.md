# 08 - Async Await Error Handling

This lesson shows two ways to handle errors from async functions: inside the function with `try...catch` and outside with `.catch()`.

## Files

- `index.html` loads the async error handling examples and includes `script.js`.
- `script.js` contains the async fetch error handling examples.

## What This Covers

- Wrapping awaited fetch calls in `try...catch`.
- Checking `response.ok` with async/await.
- Throwing custom request errors.
- Reading response text with `await`.
- Letting an async function reject.
- Handling rejected async functions with `.catch()`.

## Things To Notice

The active `getPosts()` call uses `.catch()` outside the function. The commented `getUsers()` example handles errors inside the function with `try...catch`.
