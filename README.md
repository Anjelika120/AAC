# Aus Asia Connect

Marketing website for Aus Asia Connect — a partner for companies and educational
programs expanding across the Australia–Asia corridor.

## What this is

A single-page static site. No build step, no backend.

- `index.html` — the entire site
- `assets/` — logo files (colour + white)
- `image-slot.js` — drag-and-drop image placeholders
- `tweaks-panel.jsx` — design-time controls (hidden for visitors)

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works. No build command; output/root directory is `/`.

- **Cloudflare Pages** — Connect to Git → Framework preset: None → Build command: (blank) → Output: `/`
- **Netlify / Vercel** — Import the repo → no build settings needed → Deploy

Every push to `main` redeploys automatically.
