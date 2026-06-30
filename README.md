# Froggo 🐸

A minimal, zero-dependency expense tracker that runs entirely in the browser. No server, no build step, no accounts — just open `index.html` and start logging.

## Features

- **Add, edit, and delete expenses** via slide-up bottom sheets
- **Monthly totals** with a configurable billing cycle start day (e.g. track from the 15th)
- **Auto emoji** — descriptions like "coffee" or "groceries" get a matching emoji automatically
- **Smart suggestions** — previously used descriptions surface as quick-tap chips
- **Month navigation** with a slide animation
- **Dark theme**, mobile-first layout, works as a PWA / Add to Home Screen on iOS

## Usage

Open `index.html` in any browser. Everything is stored in `localStorage` — no data leaves your device.

To host it, drop `index.html`, `favicon.png`, and `favicon.svg` on any static file server or GitHub Pages.

## No dependencies

Single HTML file. Vanilla JS, vanilla CSS. The only external resource is the Google Material Icons font for button icons.

## License

[MIT](LICENSE)
