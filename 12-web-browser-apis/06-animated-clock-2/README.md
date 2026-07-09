# 06 - Animated Clock 2

This lesson extends the canvas clock with user-controlled colors and a save-to-image feature.

## Files

- `index.html` contains the canvas and color controls.
- `script.js` contains the customizable clock logic.
- `style.css` styles the clock page and controls.

## What This Covers

- Reading color input values.
- Applying control values to canvas drawing styles.
- Drawing a customizable analog clock.
- Updating the clock continuously with `requestAnimationFrame()`.
- Exporting canvas content with `toDataURL()`.
- Creating a temporary download link.
- Downloading the clock as a PNG image.

## Things To Notice

The save button turns the current canvas drawing into an image download. The colors are read every frame, so changing an input updates the clock immediately.
