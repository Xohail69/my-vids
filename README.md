# Nikah Invitation — Dil Nisha weds Mohd. Arbaaz Rayeen

An animated, self-contained HTML invitation card (9:16, mobile-first), live at
**https://xohail69.github.io/wedding-invitation/**

- `index.html` — the whole invitation: inline CSS, inline SVG art, the music,
  and a small script that sequences the nine scenes. No build step; the only
  external request is the Google Fonts stylesheet.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Music

Tapping **Play invitation** also starts a soft plucked arpeggio in maqam Hijaz
over a low drone. It is generated in the browser with the Web Audio API, so
there is no audio file to download and nothing to license. The note button in
the bottom-right corner mutes and unmutes it.

To use your own track instead, drop the file next to `index.html` and name it
near the top of the `MUSIC_SRC` line in the script:

```js
const MUSIC_SRC = 'music.mp3';   // '' = use the generated score
```

Everything else stays the same — it loops, fades in and out with the card, and
the mute button still works.

## Viewing locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```
