# 04 - DOM Selectors Multiple Elements

This lesson covers selecting groups of DOM elements and working with NodeLists and HTMLCollections.

## Files

- `shopping-list/index.html` contains the shopping list page used for selector practice.
- `shopping-list/script.js` contains the multiple-element selector examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Selecting multiple elements with `querySelectorAll()`.
- Reading and changing items by index.
- Looping through a NodeList with `forEach()`.
- Removing elements from the page.
- Replacing item HTML with `innerHTML`.
- Selecting elements with `getElementsByClassName()`.
- Converting an HTMLCollection into an array.
- Selecting elements with `getElementsByTagName()`.

## Things To Notice

`querySelectorAll()` returns a NodeList that supports `forEach()`, while `getElementsByClassName()` returns an HTMLCollection that needs to be converted before using array methods.
