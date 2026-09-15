# Nikah Invitation — Dil Nisha weds Mohd. Arbaaz Rayeen

An animated, self-contained HTML invitation card (9:16, mobile-first).

- `index.html` — the whole invitation: inline CSS, inline SVG art, and a small
  script that sequences the nine scenes. No build step, no dependencies other
  than the Google Fonts stylesheet it links.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Viewing locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Hosting on GitHub Pages

In the repository: **Settings → Pages → Build and deployment**, set
*Source* to **Deploy from a branch**, pick this branch and the `/ (root)`
folder, then **Save**. The card is published at
`https://xohail69.github.io/my-vids/` a minute or two later.
