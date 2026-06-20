# Filter Items

This lesson adds live filtering so users can search the visible shopping list items.

## Files

- `index.html` includes the filter input and list markup.
- `style.css` styles the shopping list and filter field.
- `script.js` adds the `filterItems()` handler.
- `images/note.png` is used in the page header.

## What This Covers

- Listening for the filter input's `input` event.
- Reading and lowercasing the search text.
- Comparing each list item's text against the filter text.
- Showing matching items and hiding non-matching items.

## Things To Notice

- Filtering only changes each item's `display` style; it does not remove anything from the DOM.
- The comparison uses lowercase values so the search is case-insensitive.
