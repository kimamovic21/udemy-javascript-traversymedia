# 11 - Custom insertAfter Challenge

This challenge builds a custom `insertAfter()` helper by combining parent and sibling traversal with `insertBefore()`.

## Files

- `11-custom-insertafter.md` contains the challenge instructions and solution.
- `shopping-list/index.html` contains the shopping list page used for the challenge.
- `shopping-list/script.js` contains the `insertAfter()` solution.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Creating a reusable function with `newEl` and `existingEl` parameters.
- Creating a new list item with `document.createElement()`.
- Selecting the existing list item to insert after.
- Finding a parent with `parentElement`.
- Finding the next sibling with `nextSibling`.
- Using `insertBefore()` to simulate an insert-after operation.

## Things To Notice

There is no built-in `insertAfter()` method. The trick is to insert the new element before the existing element's next sibling.
