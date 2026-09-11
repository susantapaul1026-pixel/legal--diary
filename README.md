# The Docket — installable app

This folder is a complete Progressive Web App (PWA). Once it's hosted online,
you can add it to your phone's home screen and it opens full-screen with its
own icon, like any other app — no App Store needed.

**Data storage:** entries save to your browser's local storage, on-device.
They stay put between visits, but they're per-browser/per-device — there's
no sync between your phone and laptop.

## 1. Host it (pick one, all free)

**Netlify (easiest — drag and drop):**
1. Go to https://app.netlify.com/drop
2. Drag this whole `docket-pwa` folder onto the page
3. You'll get a live URL in seconds

**GitHub Pages:**
1. Create a new GitHub repo, upload these files
2. Go to Settings → Pages → set source to the main branch
3. Your app is live at `https://yourusername.github.io/reponame`

**Vercel:**
1. Go to https://vercel.com/new
2. Import or drag-and-drop this folder
3. Deploy

## 2. Install it on your phone

**iPhone (Safari):**
1. Open your hosted URL in Safari
2. Tap the Share icon → **Add to Home Screen**
3. Tap Add — the Docket icon now appears on your home screen

**Android (Chrome):**
1. Open your hosted URL in Chrome
2. Tap the ⋮ menu → **Add to Home screen** (or you'll see an install prompt)
3. Tap Add/Install

Once installed, it opens without any browser bar, works offline, and keeps
your case entries saved locally.

## Files in this folder
- `index.html` — the app itself
- `manifest.json` — tells the phone the app's name, icon, and colors
- `sw.js` — service worker, enables offline use
- `icons/` — app icons
