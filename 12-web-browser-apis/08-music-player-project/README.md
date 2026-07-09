# 08 - Music Player Project

This project builds a custom music player with song switching, album art, play/pause state, and a clickable progress bar.

## Files

- `index.html` contains the music player UI.
- `script.js` contains the player state and event handlers.
- `style.css` styles the music player.
- `images/` contains album cover images.
- `music/` contains the MP3 tracks.

## What This Covers

- Loading song titles, audio files, and cover images.
- Tracking the current song index.
- Playing and pausing audio.
- Updating button icons based on player state.
- Moving to the previous or next song.
- Looping through the song list.
- Updating a progress bar during playback.
- Seeking audio by clicking the progress container.

## Things To Notice

The player keeps the song names in one array and uses each name to load both the matching `.mp3` and `.jpg` files.
