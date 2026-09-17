# Wordkeeper — Voice Vocabulary Tutor

A single-page, self-contained voice vocabulary practice app.

## How to run it
Just open `index.html` in a browser — no build step, no server, no dependencies.
Double-click the file, or run a local server (e.g. `python3 -m http.server`) and visit it in your browser.

## Browser support
- **Speech playback** (the app speaking each word) works in every modern browser.
- **Voice recognition** (listening to your spoken answers) needs Chrome or Edge — desktop or Android.
  Other browsers (Safari, Firefox) automatically fall back to a text input box.
- Microphone access must be allowed by the browser the first time you tap the mic button.

## Features
- Three practice modes: use it in a sentence, repeat it for pronunciation, or define it yourself.
- Default list of 10 vocabulary words, or paste your own comma-separated list.
- Animated "conversation" visual — Wordkeeper's avatar lights up while it talks, yours lights up while it's listening.
- Previous / Next navigation between words, with your earlier answers preserved.
- In-app help for unblocking microphone access if it's been denied.
- Session summary with a pass/retry breakdown per word.

## Files
- `index.html` — everything (HTML, CSS, and JavaScript) in one file.
