# 01 - Fetch Basics

This lesson introduces the `fetch()` API for loading text, JSON, and API data.

## Files

- `index.html` loads the fetch basics page and includes `script.js`.
- `script.js` contains the fetch examples.
- `movies.json` provides local JSON data.
- `test.txt` provides local text data.

## What This Covers

- Fetching a local JSON file.
- Converting a response to JSON with `.json()`.
- Fetching a local text file.
- Converting a response to text with `.text()`.
- Fetching data from a public API.
- Updating page content with fetched API data.
- Chaining `.then()` calls from a fetch request.

## Things To Notice

The response object is not the final data. You still need to call `.json()` or `.text()` to read the response body.
