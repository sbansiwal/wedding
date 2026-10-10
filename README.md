# Sunil & Gomti — wedding site

Static, single-page site for the QR code on the wedding card. No build step.

## Deploy to GitHub Pages
1. Create a public repo named `wedding` under the `sbansiwal` account.
2. Push these files to its `main` branch (keep `index.html` at the root).
3. In the repo: Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
4. The site is live at https://sbansiwal.github.io/wedding/ within a minute or two.

## Files
- `index.html` — the whole site (markup, styles and scripts)
- `assets/couple.webp` / `couple.png` — the cartoon couple cut-out used in the hero
- `assets/invite.mp4` — the 59s invitation video (web-compressed)
- `assets/poster.jpg` — still shown before the video plays
- `assets/og.jpg` — preview image shown when the link is shared on WhatsApp
- `assets/fonts/` — self-hosted fonts (Great Vibes, Cormorant Garamond, Jost, Noto Serif Devanagari)

## Editing
All event times, names and the Google Maps link are plain text inside `index.html`. Search for "Chitrakoot" or a time like "8:00 PM" to find them.
