# 04 - requestAnimationFrame

This lesson introduces `requestAnimationFrame()` for smoother browser animations.

## Files

- `index.html` loads the animation page and includes `script.js`.
- `script.js` contains the animation loop.
- `ball.png` is the image being animated.

## What This Covers

- Starting an animation with `requestAnimationFrame()`.
- Receiving a timestamp in the animation callback.
- Tracking elapsed animation time.
- Updating CSS transforms from JavaScript.
- Translating and rotating an image.
- Stopping the animation after a duration.

## Things To Notice

`requestAnimationFrame()` syncs updates with the browser's paint cycle, which is usually smoother than using `setInterval()` for visual animation.
