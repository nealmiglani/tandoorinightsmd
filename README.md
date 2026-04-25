# Tandoori Nights — Website

Fine dining Indian restaurant in Kentlands, Gaithersburg, Maryland. Twenty-five years on Market Street.

**Live site:** [tandoorinightsmd.com](https://tandoorinightsmd.com) (production) · GitHub Pages preview after deploy.

## Stack

Static HTML + CSS. No build step. No JavaScript framework. Drop into any web host.

## Pages

- `index.html` — homepage
- `menu.html` — full menu
- `about.html` — story
- `catering.html` — catering & private events
- `visit.html` — hours, directions, reservations

## Assets

- `styles.css` — design system
- `extracted/assets/` — wordmark, ornaments, pattern files
- `extracted/photos/` — food and dining-room photography
- `sitemap.xml`, `robots.txt` — SEO

## Local development

Open `index.html` directly in a browser, or:

```sh
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

Auto-deployed via GitHub Pages from `main`. Visit Settings → Pages to verify.
