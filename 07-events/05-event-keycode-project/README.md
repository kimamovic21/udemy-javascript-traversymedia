# 05 - Event Keycode Project

This mini project displays information about the key pressed by the user.

## Files

- `event-keycodes/index.html` contains the keycode display page.
- `event-keycodes/script.js` contains the keydown handler and DOM creation code.
- `event-keycodes/style.css` styles the keycode display.

## What This Covers

- Listening for `keydown` events on the window.
- Reading `e.key`, `e.keyCode`, and `e.code`.
- Handling the space key with a custom display value.
- Clearing existing page content before rendering new results.
- Creating elements with `document.createElement()`.
- Creating labels and values with text nodes.
- Looping through an object with `for...in`.

## Things To Notice

The second implementation builds each display box with DOM methods instead of one large `innerHTML` string. That keeps the rendering logic more structured.
