# 05 - Animated Clock 1

This lesson builds an animated analog clock with the Canvas API and `requestAnimationFrame()`.

## Files

- `index.html` loads the clock canvas and includes `script.js`.
- `script.js` contains the canvas clock drawing and animation loop.

## What This Covers

- Drawing a clock face on canvas.
- Saving and restoring canvas state.
- Moving the canvas origin with `translate()`.
- Rotating the drawing context.
- Drawing hour and minute tick marks.
- Reading the current time from `Date`.
- Drawing hour, minute, and second hands.
- Re-rendering the clock with `requestAnimationFrame()`.

## Things To Notice

The canvas is rotated so the hands can be drawn from the center using angles that match a clock face. Each frame clears and redraws the entire clock.
