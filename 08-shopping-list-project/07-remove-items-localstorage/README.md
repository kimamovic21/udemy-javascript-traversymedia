# Remove Items From Local Storage

This lesson keeps local storage in sync when users remove items or clear the list.

## Files

- `index.html` contains the project markup.
- `style.css` provides the shopping list styles.
- `script.js` adds storage removal logic and an app `init()` function.
- `images/note.png` is used in the header.

## What This Covers

- Removing a single item from the DOM and storage.
- Filtering the stored array to exclude the removed item.
- Clearing all saved items with `localStorage.removeItem()`.
- Grouping event listener setup inside `init()`.

## Things To Notice

- `removeItemFromStorage()` uses the list item's text content to decide which stored item to remove.
- The app now restores, removes, and clears persisted list data across refreshes.
