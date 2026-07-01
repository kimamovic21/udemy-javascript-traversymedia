# 02 - setInterval clearInterval

This lesson introduces repeated timers with `setInterval()` and shows how to stop them with `clearInterval()`.

## Files

- `index.html` loads the interval demo page and includes `script.js`.
- `script.js` contains the interval start and stop examples.

## What This Covers

- Running repeated work with `setInterval()`.
- Saving an interval id.
- Preventing multiple intervals from stacking.
- Generating a random hex color.
- Updating the page background color repeatedly.
- Stopping repeated work with `clearInterval()`.
- Wiring start and stop buttons to timer functions.

## Things To Notice

`startChange()` checks whether an interval already exists before starting a new one. Without that guard, clicking start repeatedly would create multiple active intervals.
