# 02 - Map Position

This lesson combines geolocation with Leaflet and OpenStreetMap tiles to display the user's location on a map.

## Files

- `index.html` loads the map page and Leaflet dependencies.
- `script.js` contains the map, marker, and geolocation logic.

## What This Covers

- Creating a Leaflet map with `L.map()`.
- Adding OpenStreetMap tiles.
- Creating and updating a map marker.
- Reading the user's latitude and longitude.
- Centering the map on the user's position.
- Binding a popup to a marker.

## Things To Notice

The map starts at `[0, 0]` and then moves when geolocation succeeds. If permission is denied, the marker stays at the default location.
