# Clear UI State

This lesson updates the interface when the shopping list is empty or populated.

## Files

- `index.html` includes the form, filter input, item list, and clear button.
- `style.css` styles the project UI.
- `script.js` adds a `checkUI()` function to hide or show controls based on the current list.
- `images/note.png` is the page header image.

## What This Covers

- Querying all current list items with `querySelectorAll()`.
- Hiding the filter input and clear button when no items exist.
- Showing those controls again after items are added.
- Calling shared UI-state logic after add, remove, and clear actions.

## Things To Notice

- `checkUI()` centralizes display logic so each event handler does not repeat the same visibility checks.
- The lesson introduces the filter input in the UI, but filtering behavior is added in the next step.
