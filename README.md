# Kishore V — Developer Portfolio

A responsive, single-page developer portfolio built with HTML, CSS, and vanilla JavaScript. It features a scroll-driven architectural environment rendered with Three.js 0.186.0, project case-study modals, responsive navigation, and reduced-motion support. Three.js is loaded from a pinned CDN build; the page keeps a CSS architectural fallback if WebGL or the CDN is unavailable.

## Run locally

No package manager or build step is required. Serve the folder over HTTP to load the Three.js module; opening the HTML file directly keeps the static fallback.

1. Open `index.html` in a browser, or serve the folder locally.

For a local server, from this folder run:

```bash
python -m http.server 5500
```

Then open `http://localhost:5500`.

## Deploy

### Netlify
Deploy this repository root with Netlify Drop, or connect the GitHub repository.

### GitHub Pages
Create a repository, upload `index.html` and the `assets` folder, then enable Pages from the repository settings.

## Project files

- `index.html` — page markup, design tokens, Three.js scene, and interactions
- `assets/kishore-photo.png` — hero portrait

## External assets

Google Fonts, Tailwind CSS, and Three.js are loaded from CDNs. Fonts have system fallbacks. The site has no package manager or production build step.

The SME Decision Simulator case study links to its deployed application at <https://sme-decision-simulator.vercel.app>. Other projects link to the GitHub profile until their live deployment URLs are confirmed. Smart Trolley is marked completed. No resume file is included in this repository.
