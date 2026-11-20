<p align="center">
  <img src="icon-192.png" width="96" alt="Æramyd logo">
</p>

<h1 align="center">Æramyd</h1>
<p align="center">Small, well-made apps.</p>
<p align="center"><a href="https://aeramyd.pages.dev">aeramyd.pages.dev</a></p>

---

The home of Æramyd, an independent app studio. The site has a live snap demo from **Æramyd Sketch**: draw a rough shape, lift, and it turns clean.

## Apps

| App | Link |
|---|---|
| Æramyd Sketch | [aeramyd-sketch.pages.dev](https://aeramyd-sketch.pages.dev) |
| Æramyd Notes | [aeramyd-notes.pages.dev](https://aeramyd-notes.pages.dev) |
| Æramyd Plot | [aeramyd-plot.pages.dev](https://aeramyd-plot.pages.dev) |

## Files

| File | What it is |
|---|---|
| `index.html` | Home page (styles and script inside) |
| `sketch.html`, `notes.html`, `plot.html` | App pages, served at `/sketch`, `/notes`, `/plot` |
| `privacy.html` | Privacy page, served at `/privacy` |
| `404.html` | Page-not-found screen |
| `manifest.webmanifest` | Name and icons for home-screen shortcuts |
| `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `icon-*.png` | Icons |
| `apps/` | Official app icons (Sketch, Notes, Plot) |
| `og-image.png` | Preview image for link sharing (1200×630) |
| `_headers` | Cloudflare security and caching headers |
| `robots.txt`, `sitemap.xml` | Search engines |
| `sketch.html`, `notes.html`, `plot.html` | App pages, served at `/sketch`, `/notes`, `/plot` |
| `5f2664c1a5df3318c3de33a8dfcf4e10.txt` | IndexNow key for Bing (keep it) |

Plain HTML, CSS and JavaScript. No framework, no build step.

## Deploy

Cloudflare Pages → Create → Import Git repository → `aeramyd`. Project name `aeramyd`, branch `main`, framework **None**, build command and output folder left empty. Every commit redeploys automatically.

## Brand

The Æramyd name and logo are not covered by any code license and may not be reused.

<p align="center"><sub>© 2026 Æramyd</sub></p>
