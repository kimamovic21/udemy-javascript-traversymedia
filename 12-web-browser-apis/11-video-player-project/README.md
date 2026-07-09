# 11 - Video Player Project

This project builds a custom video player with play/pause, stop, timestamp, and progress controls.

## Files

- `index.html` contains the custom video player UI.
- `script.js` contains the video player behavior.
- `style.css` styles the player controls.
- `media/` contains the video file and poster image.

## What This Covers

- Toggling play and pause from the video or button.
- Stopping video playback.
- Updating the play button icon.
- Calculating progress from current time and duration.
- Formatting the timestamp as minutes and seconds.
- Seeking by changing the progress control.
- Listening for media events like `play`, `pause`, and `timeupdate`.

## Things To Notice

The progress value is calculated as a percentage of video duration, then used in reverse to set `currentTime` when the user changes the progress control.
