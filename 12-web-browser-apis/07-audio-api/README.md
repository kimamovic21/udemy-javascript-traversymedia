# 07 - Audio API

This lesson introduces basic control of an HTML audio element with JavaScript.

## Files

- `index.html` contains the audio player controls.
- `script.js` contains the audio control logic.
- `summer.mp3` is the audio file used by the example.

## What This Covers

- Selecting an audio element.
- Playing audio with `.play()`.
- Pausing audio with `.pause()`.
- Stopping audio by resetting `currentTime`.
- Reading playback time during `timeupdate`.
- Updating volume from an input control.

## Things To Notice

HTML media elements provide built-in playback properties and methods. The custom buttons simply call those methods from event handlers.
