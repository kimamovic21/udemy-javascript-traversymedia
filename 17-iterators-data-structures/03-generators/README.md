# 03 - Generators

This lesson introduces generator functions as a cleaner way to create iterators.

## Files

- `index.html` loads the generator example in the browser.
- `script.js` defines `createTeamIterator()` with `function*` and yields team names from an array.

## What This Covers

- Creating generator functions with `function*`.
- Pausing and resuming execution with `yield`.
- Calling `next()` on a generator iterator.
- Reading the final `done` state.
- Using generators with `for...of`.
- Expanding generator output with the spread operator.
- Destructuring values from a generator.

## Things To Notice

Generators produce iterable iterator objects automatically, so they remove most of the manual iterator setup from the previous lesson.
