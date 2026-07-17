# 02 - Iterators

This lesson shows how JavaScript iterator objects work and how to make a custom object iterable.

## Files

- `index.html` loads the iterator example in the browser.
- `script.js` creates a custom iterable `app` object that returns baseball teams one at a time.

## What This Covers

- The iterator protocol.
- Returning `{ value, done }` objects from `next()`.
- Adding `[Symbol.iterator]` to an object.
- Keeping iterator state with a private `nextIndex` variable.
- Looping over a custom iterable with `for...of`.

## Things To Notice

The commented-out first version manually calls `next()`. The active version adds `[Symbol.iterator]`, which lets the object work naturally with `for...of`.
