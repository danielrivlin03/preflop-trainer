# Preflop Trainer

A preflop range trainer, installable as an app from https://venerable-queijadas-e8fc57.netlify.app.

- `preflop-trainer/` holds the app: `index.html` (the whole trainer), the app manifest, the offline worker (`sw.js`) and icons.
- Netlify publishes that folder automatically on every push to `main` (see `netlify.toml`).
- When the icons or `manifest.webmanifest` change, bump `VERSION` in `sw.js` so installed copies fetch them.
