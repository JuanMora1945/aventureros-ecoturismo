# Aventureros Ecoturismo

Landing page for **Aventureros Ecoturismo**, a travel agency in Cali, Colombia that runs eco-trips to 19 destinations in Colombia and the Caribbean.

**Live site:** https://aventureros-ecoturismo.netlify.app

## Features

- Trip filters by plan type: waterfalls, rivers, beaches, hot springs and more
- Interactive map of every destination (Leaflet)
- Light and dark mode
- Responsive layout with direct WhatsApp contact

## Stack

HTML, CSS and vanilla JavaScript in a single `index.html`. No build step. Deployed on Netlify.

## Project structure

- `sitio/` – the published site: `index.html`, `img/`, `robots.txt`, `netlify.toml`
- `fuentes/` – working files for the 3D character (`blender/` and `models/`); not deployed

## Run locally

```bash
cd sitio
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploy

```bash
cd sitio
netlify deploy --prod --dir .
```
