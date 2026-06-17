# 08 - Create Item innerHTML vs createElement

This lesson compares a quick `innerHTML` approach with a more explicit `createElement()` approach for building list items.

## Files

- `shopping-list/index.html` contains the shopping list page used for item creation practice.
- `shopping-list/script.js` contains both item creation approaches.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Creating list items with `document.createElement()`.
- Building item markup quickly with `innerHTML`.
- Building item markup step by step with text nodes and child elements.
- Creating a remove button and icon.
- Setting classes on dynamically created elements.
- Appending new items to the `.items` list.

## Things To Notice

The `createElement()` version is more verbose, but it gives more control over each node and avoids mixing a large HTML string into the function.
