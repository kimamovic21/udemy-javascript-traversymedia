# 09 - Drum Machine Project

This project creates a keyboard-controlled drum machine with audio samples and visual key feedback.

## Files

- `index.html` contains the drum key markup and audio elements.
- `script.js` contains the keyboard event logic.
- `style.css` styles the drum machine.
- `sounds/` contains the WAV sound samples.

## What This Covers

- Listening for `keydown` events.
- Matching keyboard events to elements with `data-key` attributes.
- Selecting matching audio and key elements.
- Restarting a sound by resetting `currentTime`.
- Playing audio samples from JavaScript.
- Adding and removing a visual active class.

## Things To Notice

Resetting `audio.currentTime` to `0` lets the same sound play rapidly if you press the same key several times in a row.
