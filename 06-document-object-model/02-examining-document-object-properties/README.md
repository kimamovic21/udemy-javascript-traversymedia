# 02 - Examining Document Object Properties

This lesson explores built-in document properties and collections available from the browser DOM.

## Files

- `shopping-list/index.html` contains the shopping list page used for DOM inspection.
- `shopping-list/script.js` contains the document property examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Inspecting `document.all`, `documentElement`, `head`, and `body`.
- Reading document metadata such as `doctype`, `URL`, `characterSet`, and `contentType`.
- Accessing forms with `document.forms`.
- Reading and changing form properties.
- Accessing links and images through document collections.
- Converting an `HTMLCollection` into an array with `Array.from()`.

## Things To Notice

Some document collections are array-like but not true arrays. Converting them with `Array.from()` makes array methods like `forEach()` available.
