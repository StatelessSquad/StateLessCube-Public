# StateLess-Cube — public product page

The marketing page for **StateLess-Cube**, a high pace merge tile game by
[StateLess Squad](https://github.com/StatelessSquad).

This repository contains **only the product page** — the game itself is not
published here. The page is a static site: no build step, no dependencies, no
tracking.

## What is in here

```
index.html              the page
assets/style.css        the design system
assets/app.js           reveal, count-up and the lazy demo video
assets/demo.mp4         gameplay capture
assets/shots/*.webp     screenshots
assets/icon.png         the app icon
```

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Deployment

GitHub Pages, deployed from `main` by `.github/workflows/pages.yml`.

## Developed by StateLess Squad

<https://github.com/StatelessSquad>
