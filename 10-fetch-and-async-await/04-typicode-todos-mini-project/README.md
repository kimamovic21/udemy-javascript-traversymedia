# 04 - Typicode Todos Mini Project

This mini project uses the JSONPlaceholder todos API to fetch, create, update, and delete todo items.

## Files

- `index.html` contains the todos app page.
- `script.js` contains the fetch requests and todo UI logic.
- `style.css` styles the todos app.

## What This Covers

- Fetching an initial list of todos.
- Limiting API results with a query string.
- Creating todo elements in the DOM.
- Storing ids in `data-id` attributes.
- Sending POST requests to create todos.
- Sending PUT requests to update completed state.
- Sending DELETE requests to remove todos.
- Using event delegation for todo clicks and double-clicks.

## Things To Notice

Clicking a todo toggles its completed state, while double-clicking removes it. The API calls demonstrate the request patterns even though JSONPlaceholder does not persist changes permanently.
