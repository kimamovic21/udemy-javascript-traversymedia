# Add Items

This lesson adds the first interactive behavior to the shopping list by creating list items from form input.

## Files

- `index.html` contains the shopping list form and list container.
- `style.css` styles the page and list item layout.
- `script.js` selects the form, input, and list, then creates new list items in the DOM.
- `images/note.png` is the header image used by the app.

## What This Covers

- Handling the form `submit` event.
- Preventing the default form refresh with `e.preventDefault()`.
- Reading the input value and validating empty submissions.
- Creating list items and remove buttons with `document.createElement()`.

## Things To Notice

- `createButton()` and `createIcon()` split the remove-button markup into reusable helper functions.
- At this point, remove buttons are created visually but do not remove items yet.
