# 04 - Keyboard Events

This lesson introduces keyboard events and shows how to read key details from the event object.

## Files

- `shopping-list/index.html` contains the shopping list page used for keyboard event practice.
- `shopping-list/script.js` contains the keyboard event examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Listening for `keypress`, `keyup`, and `keydown`.
- Reading the pressed key with `e.key`.
- Checking older key codes with `e.keyCode`.
- Reading physical key location with `e.code`.
- Detecting repeated keydown events with `e.repeat`.
- Checking modifier keys with `shiftKey`, `ctrlKey`, and `altKey`.
- Responding to key combinations like Shift + K.

## Things To Notice

Most of the useful keyboard information is available from the `keydown` event. Try pressing Enter, holding a key down, and using modifier keys while the item input is focused.
