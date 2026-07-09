# 14 - Speech Synthesis

This lesson uses the Speech Synthesis API to speak user-entered text with a selected browser voice.

## Files

- `index.html` contains the text input, voice selector, and form.
- `script.js` contains the speech synthesis logic.
- `style.css` styles the page.

## What This Covers

- Accessing `window.speechSynthesis`.
- Reading available browser voices.
- Populating a voice select element.
- Marking the default voice.
- Creating a `SpeechSynthesisUtterance`.
- Assigning the selected voice.
- Speaking text with `synth.speak()`.
- Handling delayed voice loading with `onvoiceschanged`.

## Things To Notice

Some browsers load voices asynchronously, so the script handles `speechSynthesis.onvoiceschanged` to populate the voice list when voices become available.
