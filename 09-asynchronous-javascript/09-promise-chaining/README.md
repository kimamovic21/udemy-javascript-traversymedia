# 09 - Promise Chaining

This lesson shows how values returned from one `.then()` callback flow into the next callback in a promise chain.

## Files

- `index.html` loads the promise chaining demo and includes `script.js`.
- `script.js` contains the chained promise example.

## What This Covers

- Returning data from a `.then()` callback.
- Passing returned values into the next `.then()`.
- Transforming data step by step in a chain.
- Handling rejected promises with `.catch()`.
- Returning a fallback value from `.catch()`.
- Continuing the chain after an error handler.

## Things To Notice

The example currently rejects, so `.catch()` runs and returns `123`. The final `.then()` still runs because the catch handler returns a normal value.
