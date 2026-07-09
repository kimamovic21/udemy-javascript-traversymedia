# 13 - Speech Recognition

This lesson uses the Speech Recognition API to listen for spoken color names and change the page background.

## Files

- `index.html` contains the speech recognition page.
- `script.js` contains the recognition setup and result handling.
- `style.css` styles the page.

## What This Covers

- Accessing `SpeechRecognition` with browser prefixes.
- Creating a speech recognition instance.
- Setting recognition language.
- Running continuous recognition.
- Reading transcript results.
- Checking accepted spoken color names.
- Updating page background color from speech.

## Things To Notice

Speech Recognition support varies by browser. The script accepts a small list of color words and alerts when the recognized phrase is not in that list.
