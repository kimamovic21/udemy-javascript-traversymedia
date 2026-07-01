# 08 - Callback to Promise

This lesson rewrites the earlier callback-based post example using promises.

## Files

- `index.html` loads the posts demo page and includes `script.js`.
- `script.js` contains the promise-based post examples.
- `style.css` styles the posts output.

## What This Covers

- Returning a promise from an async helper function.
- Resolving after a new post is added.
- Rejecting when an error occurs.
- Rendering posts after `.then()`.
- Rendering an error message from `.catch()`.
- Comparing promise flow with callback flow.

## Things To Notice

`createPost()` returns a promise, so `getPosts` can be passed directly to `.then()` and `showError` can handle failures in `.catch()`.
