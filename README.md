# Aus Asia Connect

Marketing website for Aus Asia Connect — a partner for companies and educational
programs expanding across the Australia–Asia corridor.

## What this is

A single, self-contained `index.html`. Everything — fonts, scripts, logos, and
team photos — is embedded in that one file. No build step, no backend, no other
assets required.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

Any static host works. No build command needed.

- **Cloudflare Pages / Vercel / Netlify** — connect this repo, framework preset
  **None**, build command blank, output directory `/`. Deploy.

Every push to `main` redeploys automatically.
