# Datbit Solutions — Website

Single-page brochure site for Datbit Solutions (data & analytics consultancy).

## Files
- `index.html` — the entire site (HTML, CSS, and JS in one file)

## Editing
Open this folder in VS Code. Everything is in `index.html`:
- Brand name / logo: search for "Datbit" or "Dat<span>"
- Hero text: search for `<h1>`
- Stats numbers: search for `animateCounter` near the bottom `<script>`
- Services, contact info, etc. are in clearly labeled `<!-- SECTION --> ` comments

## Hosting (free options)
1. **GitHub Pages** — push this folder to a GitHub repo, enable Pages in repo settings, pick the main branch. Free, gets you a `yourname.github.io/repo` URL, and supports a custom domain.
2. **Netlify / Vercel** — drag-and-drop this folder onto netlify.com/drop for an instant live URL, or connect a GitHub repo for auto-deploys on every push.
3. **Cloudflare Pages** — similar drag-and-drop / Git-connected flow, free tier, fast global CDN.

Any of these work great for a static single-file site like this — no build step needed.
