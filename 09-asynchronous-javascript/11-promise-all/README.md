# 11 - Promise.all

This lesson introduces `Promise.all()` for running multiple promises and waiting for all of them to finish.

## Files

- `index.html` loads the `Promise.all()` example and includes `script.js`.
- `script.js` contains the parallel promise examples.
- `movies.json`, `actors.json`, and `directors.json` provide local JSON data.

## What This Covers

- Creating promise-returning request helpers.
- Starting multiple JSON requests.
- Creating a simple resolved promise.
- Passing promises into `Promise.all()`.
- Receiving all resolved values as an array.
- Handling any rejected promise with `.catch()`.

## Things To Notice

`Promise.all()` waits for every promise in the array. If any one promise rejects, the combined promise rejects and the `.catch()` handler runs.
