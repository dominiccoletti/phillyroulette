PHILADELPHIA NEIGHBORHOOD ROULETTE

Open index.html through a web server. The simplest options are:

1. Upload this folder to GitHub Pages, Netlify, or any static web host.
2. From this folder, run: python3 -m http.server 8000
   Then visit: http://localhost:8000

The page loads Philadelphia neighborhood boundaries from OpenDataPhilly's public GeoJSON on GitHub and uses OpenStreetMap tiles, Leaflet, and Turf.js.

The broad “section” labels are inferred from each neighborhood centroid and are meant as practical filters, not official boundaries.
