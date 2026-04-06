# Stock Market Academy — PWA

A fully installable Progressive Web App for learning stocks.

## Files
- `index.html` — the full app
- `manifest.json` — PWA metadata (name, icon, colors)
- `sw.js` — service worker (offline support)
- `icons/` — app icons (192px and 512px)

---

## How to host for FREE (choose one)

### Option A — GitHub Pages (recommended, free forever)
1. Create a free account at github.com
2. Create a new repository (e.g. `stock-academy`)
3. Upload all these files to the repo
4. Go to Settings → Pages → Source: main branch → Save
5. Your app is live at: `https://yourusername.github.io/stock-academy`

### Option B — Netlify (drag & drop, free)
1. Go to netlify.com and sign up free
2. Drag the entire folder onto the Netlify dashboard
3. Your app is live instantly with a free URL

### Option C — Vercel (free)
1. Go to vercel.com and sign up free
2. Import from GitHub or drag & drop
3. Live instantly

---

## How users install it on iPhone
1. Open the app URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — done! It appears on the home screen like a real app.

## How users install it on Android
1. Open the URL in Chrome
2. Tap the **three dots menu** → **"Add to Home Screen"**
3. Or Chrome may show an automatic install banner at the bottom

---

## Customization
- Change the app name in `manifest.json` → `"name"` field
- Change colors in `manifest.json` → `"theme_color"` and `"background_color"`
- Replace icon files in `icons/` folder with your own 192×192 and 512×512 PNG images
- The AI tutor uses the Anthropic Claude API — it works as long as the API is accessible

## Requirements
- No backend needed
- No database needed
- Works fully in the browser
- Offline support via service worker (cached after first load)
