# Citeh Enjoyment Index (CEI)

Bristol pub crawl tracker & leaderboard PWA.

## Files

- `index.html` — Main app (single page)
- `manifest.json` — PWA manifest
- `sw.js` — Service worker (offline caching)
- `icon-192.png` / `icon-512.png` — App icons

## Deploy to GitHub Pages

1. Create a new repo (or use an existing GitHub Pages repo)
2. Copy all files into the repo root (or a subfolder)
3. Push to GitHub
4. Go to **Settings → Pages → Source** and select your branch
5. Your app will be live at `https://yourusername.github.io/repo-name/`

## Add to Home Screen (PWA)

Once hosted on GitHub Pages (HTTPS required):
- **iPhone**: Open in Safari → Share → "Add to Home Screen"
- **Android**: Open in Chrome → Menu → "Add to Home Screen"

## Features

- 🗺 Interactive map of all 9 stops with route line
- ⚙ Add up to 12 people and customize 3 activities
- ✅ Per-location tracking matrix (visited + activities)
- 🏆 Live leaderboard with podium and scores
- 💾 Export/import data as JSON
- 📱 Works offline after first load

## Scoring

- **+1** per venue visited
- **+1** per activity completed
- **+0.5** for half-completed activities
- Tesco pit stop has 1 activity (Drink Water); all other venues have 3 customizable activities
