# Chingham's Musical Tool (PWA)

Installable Progressive Web App — tuner, chords, scales, metronome and more for guitar, sitar, ukulele and many other instruments.

## Features
- Works offline after first visit
- **Install as an app** on Android, desktop Chrome/Edge, and iOS (Add to Home Screen)
- Microphone tuner (requires HTTPS — GitHub Pages provides this)
- Multi-instrument support

## Deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `chingham-musical-tool`).
2. Upload **all files** from this folder to the repo root (or a `/docs` folder):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`
3. In the repo: **Settings → Pages → Source → Deploy from branch `main` (root)** (or `/docs` if you used that).
4. After a minute, open:
   `https://YOUR_USERNAME.github.io/chingham-musical-tool/`
5. On phone or PC, open that URL and tap **Install App**.

## Local test

```bash
npx serve
```

Open `http://localhost:3000` — install may only appear on HTTPS or localhost in Chromium browsers.

## Install tips
| Platform | How |
|----------|-----|
| Android Chrome | Tap **Install App** in the tool, or browser menu → Install app |
| Desktop Chrome/Edge | **Install App** button or address-bar install icon |
| iPhone / iPad | Safari → Share → **Add to Home Screen** |

Microphone access only works on **HTTPS** or **localhost** (GitHub Pages is HTTPS).
