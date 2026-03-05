# Ladbrokes Landing Page

A modern, responsive landing page for Ladbrokes — the UK's most trusted sports betting brand.

## Live Preview

Deploy to any static hosting provider to preview. See [Deployment](#deployment) below.

## Features

- **Scroll-driven animations** — sections scale up and take over the viewport as you scroll
- **Visual benefit cards** — rich CSS backgrounds with geometric shapes (no external images needed)
- **Fully self-contained** — all assets (logo, partnership image) embedded as base64; zero external dependencies beyond Google Fonts
- **Responsive** — optimised for desktop, tablet, and mobile
- **Accessible** — semantic HTML, alt text, proper contrast ratios

## Sections

1. **Hero** — headline offer with stats bar
2. **Welcome Bonus** — step-by-step claim flow
3. **Why Ladbrokes** — six visual feature cards
4. **Partnerships** — Liverpool FC official betting partner
5. **Trust & Safety** — UKGC, SSL, GamStop, IBAS
6. **Final CTA** — conversion section with responsible gambling messaging

## Tech Stack

- Vanilla HTML / CSS / JS (no build step)
- Google Fonts (DM Sans + Space Mono)
- IntersectionObserver API for scroll animations
- Base64-embedded images (zero external image requests)

## Deployment

### Netlify (quickest)
1. Drag the repo folder onto [app.netlify.com/drop](https://app.netlify.com/drop)
2. Done — you'll get a live URL instantly

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Vercel
1. Import the repo at [vercel.com/new](https://vercel.com/new)
2. Framework preset: **Other**
3. Deploy

### Cloudflare Pages
1. Connect the repo at [dash.cloudflare.com](https://dash.cloudflare.com) → Pages
2. Build command: _(leave blank)_
3. Output directory: `/`

## File Structure

```
ladbrokes-landing/
├── index.html          # Single-file landing page (all assets embedded)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── netlify.toml        # Netlify deploy config (optional)
```

## Legal

This is an internal marketing asset. All Ladbrokes branding, trademarks, and logos are property of Entain plc.

---

*18+ | BeGambleAware.org | Please bet responsibly*
