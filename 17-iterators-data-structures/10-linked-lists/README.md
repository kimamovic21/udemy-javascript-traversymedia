# 10 - Linked Lists

This lesson builds a basic linked list with node objects and a list class.

## Files

- `index.html` loads the linked list example in the browser.
- `script.js` defines `Node` and `LinkedList` classes and demonstrates inserting, removing, reading, printing, and clearing list data.

## What This Covers

- Creating nodes with a value and `next` pointer.
- Tracking the head of a linked list.
- Inserting at the beginning of the list.
- Inserting at the end of the list.
- Inserting at a specific index.
- Getting a node value by index.
- Removing a node by index.
- Printing the list values.
- Clearing the list.

## Things To Notice

Each node points to the next node instead of relying on array indexes. Traversal starts at the head and follows each `next` reference until the list ends.
