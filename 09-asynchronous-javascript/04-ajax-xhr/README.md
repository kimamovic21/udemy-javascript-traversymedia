# 04 - AJAX XHR

This lesson introduces AJAX requests with the older `XMLHttpRequest` API.

## Files

- `index.html` loads the AJAX demo page and includes `script.js`.
- `script.js` contains the XHR request example.
- `movies.json` provides local sample JSON data for testing.
- `style.css` styles the results output.

## What This Covers

- Creating an `XMLHttpRequest` object.
- Opening a GET request with `xhr.open()`.
- Checking `readyState` and HTTP `status`.
- Parsing JSON with `JSON.parse()`.
- Rendering response data into the DOM.
- Sending the request with `xhr.send()`.
- Comparing local JSON data with an external API endpoint.

## Things To Notice

The local `movies.json` request is commented out, while the active request uses the GitHub API. The rendering code expects an array of repository objects with `name` and `description` fields.
