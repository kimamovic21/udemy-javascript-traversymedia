# 10 - Promises vs Callback Hell

This lesson replaces nested XHR callbacks with promise chaining for a cleaner sequential async flow.

## Files

- `index.html` loads the promise request example and includes `script.js`.
- `script.js` contains the promise-based JSON request flow.
- `movies.json`, `actors.json`, and `directors.json` provide local JSON data.

## What This Covers

- Wrapping `XMLHttpRequest` in a promise.
- Resolving parsed JSON data on success.
- Rejecting with an error message on failure.
- Returning promises from `.then()` callbacks.
- Loading multiple JSON files in sequence.
- Handling request failures with `.catch()`.

## Things To Notice

Each `.then()` returns the next `getData()` call. That keeps the requests sequential without nesting callbacks deeper and deeper.
