# 15 - Date Object Methods

This lesson explores methods for reading parts of a date and formatting dates for different locales.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` creates a current date, reads pieces from it, formats it, and logs the final result.

## What This Covers

- Converting dates with `.toString()`, `.getTime()`, and `.valueOf()`.
- Reading year, month, day of month, day of week, hours, minutes, seconds, and milliseconds.
- Adjusting `.getMonth()` because JavaScript months start at `0`.
- Building a simple formatted date string manually.
- Formatting dates with `Intl.DateTimeFormat()`.
- Formatting dates with `.toLocaleString()`.
- Passing locale and timezone options.

## Things To Notice

The final `toLocaleString()` example formats the date using the `America/New_York` timezone. Changing the options object is a good way to practice custom date display.
