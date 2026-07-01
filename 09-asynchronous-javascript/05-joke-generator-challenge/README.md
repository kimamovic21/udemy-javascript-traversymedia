# 05 - Joke Generator Challenge

This challenge builds a small Chuck Norris joke generator using `XMLHttpRequest` and a public joke API.

## Files

- `09-joke-generator-project.md` contains the challenge instructions and solution walkthrough.
- `chuck-joke-generator/index.html` contains the joke generator page.
- `chuck-joke-generator/script.js` contains the XHR request and event handling code.
- `chuck-joke-generator/style.css` styles the joke generator.

## What This Covers

- Selecting the joke display element and button.
- Creating a reusable `generateJoke()` function.
- Requesting random jokes from an API with `XMLHttpRequest`.
- Checking request completion with `readyState`.
- Handling success and failure status values.
- Parsing JSON response data.
- Loading an initial joke on `DOMContentLoaded`.
- Fetching a new joke on button click.

## Things To Notice

The joke text lives in the API response's `value` property. If the request fails, the page shows a fallback error message instead of leaving the old joke in place.
