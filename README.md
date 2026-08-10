# 🎯 Algo Quest

A bite-size, Duolingo-style revision game for **CM52070 Algorithms & Complexity**.

**Play it here → https://kylezinho.github.io/algo-quest/**

## What's inside

- **12 levels across 4 units** covering the whole module, with 144 multiple-choice questions, every one with a plain-English explanation.
- **Smart Practice** — after ~10 answers it learns your weak topics and builds sessions around them (spaced repetition + topic mastery tracking).
- **Hearts, XP, combos, streaks and a daily goal** to keep revision habitual.
- **Stats screen** showing per-topic mastery and your weak spots.
- Progress is saved in your browser (localStorage) — no account, no server.

## On your phone

The game is a single HTML file, optimised for mobile, and installs as an app:

- **iPhone:** open the link in Safari → Share → **Add to Home Screen**.
- **Android:** open the link in Chrome → menu → **Add to Home screen** / **Install app**.

Once installed it works **offline** (service worker cache) — revision on the train works fine.

## Tech

Single-file vanilla JS/HTML/CSS, no build step, no dependencies. `sw.js` provides
offline caching; `manifest.webmanifest` + icons make it installable as a PWA.
Light and dark mode follow your system setting.
