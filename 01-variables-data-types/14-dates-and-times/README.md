# 14 - Dates and Times

This lesson introduces the JavaScript `Date` object, date creation, date parsing, and timestamps.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` creates several dates, converts dates to strings and timestamps, and logs the final result.

## What This Covers

- Creating a date for the current moment with `new Date()`.
- Converting a date to a readable string with `.toString()`.
- Creating specific dates with numeric arguments.
- Remembering that numeric months are zero-based in JavaScript dates.
- Creating dates from date strings.
- Getting timestamps with `Date.now()`, `.getTime()`, and `.valueOf()`.
- Creating a date from a timestamp.
- Converting milliseconds to seconds.

## Things To Notice

Date parsing can behave differently depending on the string format and timezone. The lesson includes a note about the common "one day off" issue when working with date-only strings.
