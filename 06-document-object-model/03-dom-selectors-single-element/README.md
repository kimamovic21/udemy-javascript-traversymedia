# 03 - DOM Selectors Single Element

This lesson focuses on selecting one DOM element at a time and changing its attributes, content, and styles.

## Files

- `shopping-list/index.html` contains the shopping list page used for selector practice.
- `shopping-list/script.js` contains the single-element selector examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Selecting elements with `document.getElementById()`.
- Reading attributes with direct properties and `getAttribute()`.
- Setting attributes with direct properties and `setAttribute()`.
- Updating content with `textContent`, `innerText`, and `innerHTML`.
- Changing inline styles with the `style` property.
- Selecting elements with CSS selectors using `querySelector()`.
- Calling `querySelector()` from another selected element.

## Things To Notice

`querySelector()` returns the first matching element. When it is called from `list`, the search happens inside that list instead of across the whole document.
