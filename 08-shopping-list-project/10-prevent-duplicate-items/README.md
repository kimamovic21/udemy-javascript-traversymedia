# Prevent Duplicate Items

This lesson adds duplicate checking so the same shopping list item cannot be added twice.

## Files

- `index.html` contains the completed project markup.
- `style.css` contains the shopping list and edit-mode styling.
- `script.js` adds `checkIfItemExists()` and duplicate validation.
- `images/note.png` is used in the app header.

## What This Covers

- Checking the stored items array before adding a new item.
- Showing an alert when a duplicate item is submitted.
- Allowing edit mode to replace an existing item without triggering the duplicate check too early.
- Keeping duplicate prevention tied to local storage data.

## Things To Notice

- Duplicate checking happens only when adding a new item, not while replacing the item currently being edited.
- The completed lesson now supports adding, filtering, editing, removing, clearing, and persisted storage.
