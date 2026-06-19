# 03 - Event Object

This lesson explores the event object that browser event handlers receive when an event fires.

## Files

- `shopping-list/index.html` contains the shopping list page used for event object practice.
- `shopping-list/script.js` contains the event object examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Receiving the event object as a handler parameter.
- Inspecting event properties like `target`, `currentTarget`, and `type`.
- Reading mouse coordinates from the event object.
- Updating page text while dragging.
- Preventing default browser behavior with `preventDefault()`.
- Comparing event positions such as client, page, offset, and screen coordinates.

## Things To Notice

The link click handler calls `preventDefault()`, so the browser does not navigate away. That keeps the page available while you inspect the console output.
