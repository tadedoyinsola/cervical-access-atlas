# U.S. Cervical-Cancer Prevention Access Atlas (dashboard)

An interactive county choropleth of the structural healthcare-access index, the cervical-screening
gap, the combined priority score, and the double-burden priority counties, with a targeting slider.
Static site, hosts on GitHub Pages (like the Nigeria MVI atlas). No server or build step.

## Files
- `index.html` — the whole app (Leaflet map, layer toggle, legend, county panel, targeting slider).
- `counties.geojson` — 3,109 contiguous-US counties with all values embedded as properties.

## Preview locally
A browser will not load `counties.geojson` by double-clicking `index.html` (file:// blocks the fetch),
so run a tiny local server from this folder:

```bat
cd "%USERPROFILE%\Cervical Cancer\09_Dashboard"
python -m http.server 8000
```
Then open http://localhost:8000 in your browser.

## Deploy to GitHub Pages
1. Create a new repo, e.g. `cervical-access-atlas`.
2. Put `index.html` and `counties.geojson` in the repo root and push.
3. Repo Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. Live in a minute or two at `https://tadedoyinsola.github.io/cervical-access-atlas/`.

## Notes
- The map uses the Leaflet library and CARTO basemap tiles from their CDNs (same approach as most
  GitHub Pages maps); these load automatically online.
- Colors describe access and screening gaps, not cancer risk. Cervical incidence/mortality are shown
  for context only and were never inputs to the index. Many small, rural counties have suppressed
  cancer rates; Alaska and Hawaii are omitted.
- To change colors, breaks, or text, edit the `RAMP`, `LAYERS`, and header sections of `index.html`.
