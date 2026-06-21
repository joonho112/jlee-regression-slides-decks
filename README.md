# jlee-regression-slides-decks

This repository hosts the **74 rendered RevealJS lecture decks** for **BER 640
(Regression)** on GitHub Pages:

> https://joonho112.github.io/jlee-regression-slides-decks/

## What this is

This is a **rendered mirror** — it contains only the built HTML output, not the
source `.qmd` files. The decks are authored and rendered elsewhere, in:

```
lecture-slides-scripts/slides/_recording/
```

To update the decks: **regenerate them in that source location, then re-copy the
rendered output here.** Do not hand-edit files in this repo.

## Contents

- `decks/` — 74 self-contained RevealJS `*.html` decks
- `index.html` — deck launcher / landing page
- `figs/` — shared figure assets
- `site_libs/` — RevealJS, theme, and JS/CSS dependencies
- `search.json` — site search index
- `.nojekyll` — tells GitHub Pages to serve underscore-prefixed paths verbatim
  (without Jekyll processing)

## How it is consumed

The course's **slides book** embeds these decks via:

```
DECK_BASE = https://joonho112.github.io/jlee-regression-slides-decks/decks/
```

## Deck hosting

Published from this repo's root on the `main` branch via GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / `root`).
