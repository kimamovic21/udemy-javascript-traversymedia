# 05 - Traversing the DOM Elements

This lesson shows how to move between related DOM elements using element-only traversal properties.

## Files

- `index.html` contains the parent and child elements used for traversal practice.
- `script.js` contains the element traversal examples.
- `style.css` styles the traversal demo.

## What This Covers

- Selecting a parent element.
- Reading child elements with `children`.
- Accessing child element text, class names, and node names.
- Updating first and last child elements.
- Moving from a child to its parent with `parentElement`.
- Moving between siblings with `nextElementSibling` and `previousElementSibling`.
- Applying styles to traversed elements.

## Things To Notice

Element traversal properties skip text nodes created by whitespace in the HTML. That makes them easier to use when you only care about actual elements.
