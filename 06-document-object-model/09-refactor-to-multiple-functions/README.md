# 09 - Refactor to Multiple Functions

This lesson refactors item creation into smaller helper functions for creating list items, buttons, and icons.

## Files

- `shopping-list/index.html` contains the shopping list page used for refactoring practice.
- `shopping-list/script.js` contains the refactored element creation functions.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Creating a new list item with a dedicated function.
- Creating button elements from a helper function.
- Creating icon elements from a helper function.
- Passing class strings into reusable DOM helper functions.
- Returning created elements from helper functions.
- Appending multiple generated items to the list.

## Things To Notice

Breaking the code into `createNewItem()`, `createButton()`, and `createIcon()` keeps each function focused on one job and makes the list item builder easier to read.
