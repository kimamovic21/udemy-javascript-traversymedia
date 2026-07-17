# 04 - Profile Scroller Project

This project uses a generator to cycle through profile data and update the page when the user clicks a button.

## Files

- `profile-scroller/index.html` contains the profile card markup.
- `profile-scroller/style.css` contains the project styling.
- `profile-scroller/script.js` stores the profile data, creates the generator, and updates the DOM.

## What This Covers

- Building a small DOM project with local data.
- Creating an infinite generator with `while (true)`.
- Cycling through an array with the modulo operator.
- Handling button clicks.
- Updating image, heading, and paragraph content in the DOM.

## Things To Notice

The generator uses `index++ % people.length`, so it keeps looping back to the first profile after the last profile is shown.
