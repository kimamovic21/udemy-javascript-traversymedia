# 05 - Fetch Error Handling

This lesson explains how fetch handles HTTP errors and how to turn failed status codes into caught errors.

## Files

- `index.html` loads the fetch error handling examples and includes `script.js`.
- `script.js` contains status and network error examples.
- `random-user-generator/index.html` contains the random user app with error handling.
- `random-user-generator/script.js` contains the guarded random user fetch code.
- `random-user-generator/spinner.css` styles the random user spinner.

## What This Covers

- Testing successful and failed HTTP responses.
- Understanding that `fetch()` only rejects on network errors by default.
- Checking `response.ok`.
- Checking specific status codes.
- Throwing errors manually for failed responses.
- Catching network and manually thrown errors.
- Displaying an error message in the random user app.
- Hiding the spinner after success or failure.

## Things To Notice

A 404 or 500 response does not automatically run `.catch()`. You need to check the response and throw an error when the status is not acceptable.
