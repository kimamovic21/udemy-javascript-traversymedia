# 07 - Poll Project

This project uses a `Map` to track votes in a small favorite JavaScript framework poll.

## Files

- `index.html` contains the Bootstrap poll form and results area.
- `script.js` stores the vote counts in a map, handles form submission, validates selection, renders results, and disables the form after voting.

## What This Covers

- Creating a map for poll options and vote counts.
- Handling form submission.
- Reading the selected radio input.
- Guarding against empty submissions.
- Updating map values.
- Rendering results into the DOM.
- Iterating through map entries with `for...of`.
- Disabling form controls after a vote.

## Things To Notice

The poll options in the form match the keys in the `Map`, which makes it simple to read the selected value and update the correct vote count.
