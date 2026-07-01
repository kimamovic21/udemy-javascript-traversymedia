# 06 - Callback Hell

This lesson demonstrates callback nesting when multiple asynchronous requests depend on each other.

## Files

- `index.html` loads the callback hell example and includes `script.js`.
- `script.js` contains the nested callback request flow.
- `movies.json`, `actors.json`, and `directors.json` provide local JSON data.

## What This Covers

- Writing a reusable `getData()` function.
- Requesting local JSON files with `XMLHttpRequest`.
- Passing callback functions into async request helpers.
- Parsing JSON before passing data to a callback.
- Simulating unpredictable request timing with random delays.
- Nesting requests so they run in sequence.

## Things To Notice

The nested callbacks make the order clear, but the code becomes harder to read as each new async step is added. That is the problem promises solve in later lessons.
