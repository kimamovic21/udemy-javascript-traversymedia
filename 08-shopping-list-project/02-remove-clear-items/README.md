# Remove And Clear Items

This lesson adds item removal and a clear-all action to the shopping list.

## Files

- `index.html` contains the form, item list, and clear button.
- `style.css` keeps the shopping list layout and button styles.
- `script.js` adds click handlers for removing single items and clearing the full list.
- `images/note.png` is the note icon used in the header.

## What This Covers

- Listening for clicks on the item list and clear button.
- Detecting whether a clicked element belongs to a remove button.
- Removing a single list item from the DOM.
- Clearing all items with a `while` loop.

## Things To Notice

- The remove handler uses the clicked icon's parent elements to find the `li` that should be removed.
- The clear button removes DOM nodes only; persistence is added later with local storage.
