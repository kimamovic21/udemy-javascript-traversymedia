# 10 - Window Events

This lesson covers events that fire on the browser window rather than a specific page element.

## Files

- `index.html` contains the long page used for window event practice.
- `script.js` contains the window event examples.

## What This Covers

- Running code when the full page loads with `load`.
- Running code when the DOM is ready with `DOMContentLoaded`.
- Responding to browser resizing with `resize`.
- Reading window size with `innerWidth` and `innerHeight`.
- Responding to scrolling with `scroll`.
- Reading scroll position with `scrollX` and `scrollY`.
- Responding to window `focus` and `blur`.
- Updating page styles from window events.

## Things To Notice

`DOMContentLoaded` fires when the HTML is parsed, while `load` waits for the full page and assets. The resize and scroll handlers make visible changes as you interact with the browser window.
