# 09 - Event Delegation

This lesson demonstrates event delegation by listening on a parent list instead of every individual list item.

## Files

- `shopping-list/index.html` contains the shopping list page used for delegation practice.
- `shopping-list/script.js` contains the event delegation examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Comparing individual item listeners with a parent listener.
- Listening for clicks on the parent `ul`.
- Checking the actual clicked element with `e.target`.
- Removing list items when a clicked target is an `LI`.
- Handling `mouseover` through the same delegation idea.
- Styling delegated targets from a parent event handler.

## Things To Notice

Delegation is helpful when list items may be added or removed. The parent listener can handle matching child elements without attaching a separate listener to each one.
