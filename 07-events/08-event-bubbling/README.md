# 08 - Event Bubbling

This lesson shows how events bubble from the clicked element up through parent elements.

## Files

- `shopping-list/index.html` contains the shopping list page used for bubbling practice.
- `shopping-list/script.js` contains the event bubbling examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Attaching click listeners to nested elements.
- Seeing events fire on parent elements after a child is clicked.
- Listening on a button, containing div, form, and body.
- Stopping bubbling with `stopPropagation()`.
- Using alerts to show event order.

## Things To Notice

The button handler calls `e.stopPropagation()`, so clicking the button does not trigger the div, form, or body click handlers.
