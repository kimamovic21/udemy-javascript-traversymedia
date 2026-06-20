# Display Items From Local Storage

This lesson loads saved items from local storage and displays them when the page opens.

## Files

- `index.html` contains the shopping list markup.
- `style.css` styles the app.
- `script.js` adds display logic for stored items.
- `images/note.png` is the header image.

## What This Covers

- Moving storage reads into a reusable `getItemsFromStorage()` function.
- Rendering saved items with `displayItems()`.
- Reusing `addItemToDOM()` for both new and stored items.
- Running display logic on `DOMContentLoaded`.

## Things To Notice

- The DOM-building logic is separated from the storage logic, which makes the code easier to reuse.
- Existing storage data appears after a refresh, but removing items from storage is handled in the next lesson.
