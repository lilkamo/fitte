# Fitté — Your Personal Lookbook

A clean, modern PWA for cataloguing your outfits. Upload photos, organise by category, plan your looks, and get AI styling advice.

## Files

- `index.html` — the entire app (single file)
- `manifest.json` — PWA manifest (add to home screen)
- `sw.js` — service worker for offline support
- `icon-192.png` / `icon-512.png` — add your own app icons

## Deploy to GitHub Pages

1. Create a new repo (e.g. `fitte`)
2. Drop all files into the root
3. Go to Settings → Pages → Source: `main` / `root`
4. Your app will be live at `https://lilkamo.github.io/fitte/`

## Features

- **Looks** — upload outfit photos, name them, pick a category
- **Stylist** — AI-powered style advice using your saved looks (Claude API built in)
- **Planner** — calendar view to plan outfits ahead
- **Me** — stats and settings

## Data

All photos and look data are stored in `localStorage` — fully private, no server needed.

## Icons

Generate icons at https://realfavicongenerator.net or use any 512×512 PNG.
