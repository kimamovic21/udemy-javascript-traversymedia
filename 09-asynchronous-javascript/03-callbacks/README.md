# 03 - Callbacks

This lesson introduces callbacks as a way to run code after asynchronous work finishes.

## Files

- `index.html` loads the posts demo page and includes `script.js`.
- `script.js` contains the callback-based post examples.
- `style.css` styles the posts output.

## What This Covers

- Storing post data in an array.
- Simulating asynchronous work with `setTimeout()`.
- Passing a callback function into another function.
- Adding a new post before rendering posts.
- Creating DOM elements for each post.
- Appending generated post markup to the page.

## Things To Notice

`createPost()` takes longer than `getPosts()`, so the callback makes sure posts are rendered only after the new post has been added.
