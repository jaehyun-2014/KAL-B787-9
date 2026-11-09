# KAL B787-9 Flight Simulator

A browser-based KAL Boeing 787-9 flight simulator.

## Publish with GitHub Pages

1. Upload the simulator HTML file to this repository.
2. Rename the uploaded file to **index.html** (it must be in the repository root).
3. Open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
4. The workflow in `.github/workflows/pages.yml` will deploy the site after each push.

The simulator uses Three.js from a CDN, so an internet connection is required.
