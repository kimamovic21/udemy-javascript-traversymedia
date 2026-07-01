# 01 - setTimeout clearTimeout

This lesson introduces `setTimeout()` for delaying work and `clearTimeout()` for cancelling a scheduled timer.

## Files

- `index.html` loads the timer demo page and includes `script.js`.
- `script.js` contains the timeout and cancel examples.

## What This Covers

- Running a callback after a delay with `setTimeout()`.
- Passing an anonymous function to `setTimeout()`.
- Passing a named function to `setTimeout()`.
- Updating page text after a timer completes.
- Saving a timeout id.
- Cancelling a pending timeout with `clearTimeout()`.
- Handling a button click to cancel scheduled work.

## Things To Notice

The cancel button only matters before the timer finishes. Once the callback has already run, there is no pending timeout left to clear.
