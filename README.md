# Drone Dispatch Service: the talk

Slides for a 30-minute walkthrough of [drone-dispatch-service](https://github.com/Elikdev/drone-dispatch-service): what it does, the hard parts, and how each one was solved.

Live: https://elikdev.github.io/drone-dispatch-talk/

## Presenting

- Arrow keys or space to move between slides
- `S` opens the speaker view with notes and a timer
- `F` goes full screen, `Esc` shows all slides

## Export to PDF

1. Open the slides with `?print-pdf` at the end of the address, e.g. `https://elikdev.github.io/drone-dispatch-talk/?print-pdf`
2. Print from Chrome: destination "Save as PDF", layout landscape, margins none, and turn on "Background graphics"

## Run locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

Built with [reveal.js](https://revealjs.com) and [Mermaid](https://mermaid.js.org).
