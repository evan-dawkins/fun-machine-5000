# The Dawkinators Fun Machine 5000

A polyrhythmic arcade instrument that runs in your browser.

**Play it:** https://evan-dawkins.github.io/fun-machine-5000/

Voices orbit a ring. Voice 1 crosses the marker at the top once per cycle, voice 2 twice, voice 50 fifty times. Every crossing plays a note from the chord you pick, so the voices drift apart into dense patterns and then snap back together. Each time they all line up, a new voice joins.

## How to play

Press start with your sound on. The machine starts playing once the logo docks in the corner.

| Control | What it does |
| --- | --- |
| Root / chord type | Pick from 12 roots and 22 chord types, or switch to chromatic |
| ♯ / ♭ | Changes how note names are spelled, not the pitch |
| Voices | How many voices are in the ring (1–150) |
| Tempo | How fast the whole cycle moves |
| Dots / 123 | Show each voice as a dot or as its running hit count |
| Reset | Back to the top with counts cleared |
| Logo | Replays the intro |

## Keyboard

| Key | Action |
| --- | --- |
| Space | Play / pause |
| ← → | Change root |
| ↑ ↓ | Change chord type |
| N | Dots / numbers |
| C | Chromatic |

There may be other keys worth trying.

## How it's built

One HTML file with no build step and no dependencies beyond two Google Fonts. Sound is synthesized with the Web Audio API, the visuals are drawn on a canvas, and the announcer uses your browser's built-in text-to-speech. The announcer voice depends on your browser and operating system.

Works best in a current desktop browser. On a phone, turn the volume up and check the silent switch.
