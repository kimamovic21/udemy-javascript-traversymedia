# 06 - Traversing the DOM Nodes

This lesson compares node traversal with element traversal and shows how text nodes appear in the DOM tree.

## Files

- `index.html` contains the parent and child nodes used for traversal practice.
- `script.js` contains the node traversal examples.
- `style.css` styles the traversal demo.

## What This Covers

- Reading child nodes with `childNodes`.
- Inspecting node text content and node names.
- Accessing node HTML with `outerHTML`.
- Updating nodes with `textContent`, `innerText`, and style properties.
- Reading `firstChild` and `lastChild`.
- Moving from a child to its parent with `parentNode` and `parentElement`.
- Moving between siblings with `nextSibling` and `previousSibling`.

## Things To Notice

Node traversal includes whitespace text nodes, so the indexes can look different from element traversal. That is why `childNodes[3]` can refer to an element after whitespace nodes are counted.
