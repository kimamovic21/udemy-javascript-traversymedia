# Update Item And Reset State

This lesson completes editing by replacing the selected item and resetting the form back to add mode.

## Files

- `index.html` contains the shopping list app markup.
- `style.css` includes the normal and edit-mode styles.
- `script.js` updates selected items and resets the UI state.
- `images/note.png` is the header image used by the app.

## What This Covers

- Detecting when the form is submitted while edit mode is active.
- Removing the old item from local storage before saving the edited value.
- Removing the old DOM item and adding the updated one.
- Resetting the input, button, color, and edit state in `checkUI()`.

## Things To Notice

- Editing reuses the same submit handler used for adding new items.
- `checkUI()` now also returns the form button to its default add-item state.
