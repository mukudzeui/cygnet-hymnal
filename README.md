# Cygnet Hymnal

A projector-ready hymnal for Cygnet Private College. Type a hymn number, press Enter, and the verses are shown one slide at a time, sized to fill the screen.

## Running it

Open `index.html` in Chrome or Edge and press **F11** (or **F**) for full screen. It works offline. With no internet the page falls back to Georgia instead of the web fonts.

## Presenter keys

| Key | Action |
| --- | --- |
| `0`–`9`, Enter | Open a hymn by number (also works mid-hymn to jump to another) |
| → / Space / PageDown | Next verse (presentation clickers work) |
| ← / PageUp | Previous verse |
| Home / End | First or last slide |
| Esc | Back to the hymn number screen |
| `B` | Blank the screen |
| `T` | Switch theme: Midnight (dark), Cygnet (light), High contrast |
| `+` / `−` | Bigger or smaller lyrics |
| `D` / `R` | Doxology / Response (on the home screen type D or R, then Enter) |
| `I` | Full index |
| `?` | Presenter guide |

Typing words on the home screen instead of a number searches titles and first lines.

## Contents

- `index.html`: the app (a single page, no build step)
- `assets/hymns.js`: hymn data. Hymns 1–40 come from `Advent_Hymnal_1-40 (26).pptx` and 41–481 from `Advent_Hymnal.ppt`.
- `assets/cygnet-logo.png`, `assets/cygnet-background.png`: college branding
- `CHANGES.txt`: every correction made to the source slides (duplicates, titles, typos, verse labels)

Hymn 393 is missing: its slide in the source file was a broken copy of #27.

Made and designed by Matsika Mukudzei.
