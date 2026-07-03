# 09 - Multiple Promises Async Await

This lesson compares different ways to load multiple async resources with promises, fetch, async/await, and `Promise.all()`.

## Files

- `index.html` loads the multiple promise examples and includes `script.js`.
- `script.js` contains the sequential and parallel async request examples.
- `movies.json`, `actors.json`, and `directors.json` provide local JSON data.

## What This Covers

- Wrapping XHR requests in promises.
- Awaiting multiple requests sequentially.
- Fetching multiple local JSON files with async/await.
- Running fetch requests in parallel with `Promise.all()`.
- Destructuring resolved promise results.
- Converting multiple fetch responses to JSON.
- Comparing sequential and parallel async flows.

## Things To Notice

The active example uses `Promise.all()` with fetch calls that already convert responses to JSON, so the final destructured values are the parsed data arrays.
