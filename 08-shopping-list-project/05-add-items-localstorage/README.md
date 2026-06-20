# Add Items To Local Storage

This lesson starts persisting shopping list items in the browser's local storage.

## Files

- `index.html` contains the shopping list app structure.
- `style.css` provides the project styling.
- `script.js` adds `addItemToStorage()` and begins saving new items.
- `images/note.png` is the note icon used by the app.

## What This Covers

- Reading existing data from `localStorage`.
- Creating an array when no stored items exist yet.
- Converting the array to JSON with `JSON.stringify()`.
- Saving newly added items under the `items` key.

## Things To Notice

- This step saves newly added items, but it does not load them back into the page yet.
- Local storage stores strings, so arrays must be converted to and from JSON.
