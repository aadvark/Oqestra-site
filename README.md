# Oqestra-site

The landing page for [Oqestra](https://aadvark.github.io/Oqestra-site/), a music player for Android by Kith + Keen.

## What's here

```
index.html      The landing page (single file, no build step)
mockups/        HTML previews of the app screens, shown in the page's phone frames
downloads/      The current Android test build (oqestra.apk, now 0.6.0), linked from the download buttons,
                and latest.json, which the app reads to check for updates
images/         Widget previews
```

## Preview locally

Open `index.html` in a browser, or serve the folder so the mockup frames load:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Publishing

The site is served by GitHub Pages from the `main` branch, root folder. A push to `main` republishes it within a few minutes.

## Fonts

Bricolage Grotesque and Instrument Sans, loaded from Google Fonts.

© 2026 Kith + Keen
