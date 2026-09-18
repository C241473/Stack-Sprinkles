# Stack Sprinkles — Polyglot Environment Generator

A single self-contained `index.html` file — no build step, no install.

## Run it

- **Easiest:** double-click `index.html` to open it in your browser.
- **In VS Code:** open this folder in VS Code, install the "Live Server" extension, right-click `index.html` → "Open with Live Server".

## What's inside

Everything (HTML + CSS + JS) lives in `index.html`. It only reaches out to the internet for:
- Google Fonts (Baloo 2, Nunito, JetBrains Mono)
- JSZip (from cdnjs) — used to build the downloadable `.zip` when you click "Generate & Download ZIP"

No server, no npm install, no build tooling required.
