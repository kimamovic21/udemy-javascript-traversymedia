# 05 - HTTP Module

This lesson introduces Node's `http` module by creating a small server with an HTML route and a JSON API route.

## Files

- `http.js` creates the HTTP server, handles routes, reads the HTML file, and returns JSON data.
- `index.html` is the HTML page served at the root route.
- `urlqs.js`, `os.js`, `path.js`, and `fs.js` keep the earlier Node core module examples.

## What This Covers

- Importing Node's `http` module.
- Creating a server with `http.createServer()`.
- Reading the request URL.
- Serving an HTML file with `fs.readFile()`.
- Returning JSON from an API route.
- Setting response status codes and content types.
- Handling missing routes with a 404 response.
- Listening on a local port with `server.listen()`.

## Things To Notice

Run `http.js` from this lesson folder so `fs.readFile('index.html')` can find the HTML file beside the server script.
