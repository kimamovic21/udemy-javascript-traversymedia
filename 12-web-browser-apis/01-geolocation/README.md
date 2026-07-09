# 01 - Geolocation

This lesson introduces the browser Geolocation API for reading and watching the user's current position.

## Files

- `index.html` loads the geolocation example and includes `script.js`.
- `script.js` contains the current-position and watch-position examples.

## What This Covers

- Using `navigator.geolocation.getCurrentPosition()`.
- Handling successful position reads.
- Handling geolocation errors.
- Reading latitude, longitude, and accuracy values.
- Passing geolocation options.
- Watching position changes with `watchPosition()`.
- Stopping a watcher with `clearWatch()`.

## Things To Notice

The active code uses `watchPosition()`, so the browser may ask for location permission. Geolocation usually requires a secure context such as localhost or HTTPS.
