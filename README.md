# My ToDos — PWA

A fully offline-capable todo organiser for iOS & Android.

## Files
- `index.html` — the full app
- `manifest.json` — PWA metadata (name, icons, colours)
- `sw.js` — service worker for offline caching
- `icons/` — place your app icons here (192×192 and 512×512 PNG)

## How to deploy (free, 5 minutes)

### Option A — Netlify (easiest)
1. Go to https://netlify.com and sign up free
2. Drag the entire `todo-pwa` folder onto the Netlify dashboard
3. You'll get a URL like `https://my-todos-abc123.netlify.app`
4. Open that URL on your phone

### Option B — GitHub Pages
1. Push this folder to a GitHub repo
2. Go to Settings → Pages → Deploy from branch (main)
3. Your app will be at `https://yourusername.github.io/repo-name`

## Installing on your phone

### iPhone (Safari only)
1. Open the app URL in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — done!

### Android (Chrome)
1. Open the app URL in Chrome
2. Tap the **three-dot menu**
3. Tap **Add to Home Screen** or accept the install banner
4. Tap **Install** — done!

## Adding icons
Generate icons at https://realfavicongenerator.net or https://favicon.io
Place `icon-192.png` and `icon-512.png` in the `icons/` folder.

## Features
- Add tasks with quick-add or the full sheet (+ button)
- Categories: Personal, Work, Health, Shopping
- Priority levels with colour dots
- Due dates with overdue/soon warnings
- Subtasks with progress tracking
- Sort by manual drag, due date, or priority
- Filter by category
- Click any task title to edit inline
- 100% offline — works with no internet after first load
- All data saved locally on your device
