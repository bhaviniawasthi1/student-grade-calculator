# Gradebook

A clean, single-page grade calculator — enter marks subject-by-subject or as quick totals, and get your **percentage**, **GPA**, or **letter grade** instantly.

**Live demo:** [gradebook-live.vercel.app](https://gradebook-live.vercel.app/)

## Features

- **Two entry modes** — a full subject-wise table (subject name, obtained marks, max marks, live per-row %), or a two-field quick-totals mode for when you just want the bottom line.
- **"Same max marks for all"** — check one box, set a single max, and every subject's max field locks in sync.
- **One-click reset** — clears every field back to a blank slate.
- **Three output formats** — Percentage, GPA (scale of 10, scale of 5, or a custom max), and Letter Grade, computed consistently from the same underlying percentage.
- **Inline validation** — flags marks that exceed the max or missing values before calculating, instead of failing silently.
- **Light & dark themes**, fully responsive, zero dependencies beyond two Google Fonts.

## Tech

Plain HTML, CSS, and vanilla JavaScript — no framework, no build step, no backend. `index.html` is the entire app.

## Run locally

Just open `index.html` in a browser, or serve it with any static server:

```bash
npx serve .
```

## Deploy

This is a static site, so it deploys anywhere with zero configuration:

- **Vercel** — import this repo at [vercel.com/new](https://vercel.com/new); no build command or output directory needed.
- **GitHub Pages** — enable Pages on this repo (Settings → Pages → Deploy from branch → `main` / root).

## License

MIT © Bhavini Awasthi
