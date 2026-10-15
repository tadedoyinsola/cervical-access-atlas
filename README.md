# U.S. Cervical Cancer Prevention Access Atlas

A geospatial-intelligence atlas of structural barriers to cervical cancer prevention across 3,109
contiguous U.S. counties, built for state and county health departments, funders and policymakers,
and community and advocacy groups. Static site for GitHub Pages: no server, no build step, no API keys.

Live: https://tadedoyinsola.github.io/cervical-access-atlas/

## Files (upload all three to the repo root)
- `index.html`: the whole site (hero and headline stats, why it matters, map explorer, county
  profile, priority table, targeting tool, role guide, methods and data).
- `counties.geojson`: 3,109 counties with all scores as properties, plus national and state
  summaries in `meta`.
- `states.geojson`: state outlines drawn over the map.

## Preview locally
Double-clicking `index.html` will not load the data (browsers block `file://` fetches). From this folder:

```bat
cd "%USERPROFILE%\Cervical Cancer\09_Dashboard"
python -m http.server 8000
```
Then open http://localhost:8000.

## Deploy / update on GitHub Pages
1. In the repo, Add file → Upload files → drag in `index.html`, `counties.geojson`, `states.geojson`
   (replace the existing ones) → Commit changes.
2. Pages is already set to `main` / `(root)`. The site refreshes in a minute or two
   (hard-refresh with Ctrl+F5).

## Features
- Plain-language map layers: barrier to care, screening shortfall, combined priority,
  double-burden counties, no local OB/GYN. Hover tooltips, state outlines, YlOrRd ramp.
- County search, state filter and zoom, shareable county links (`#c=FIPS`), printable county brief,
  county-to-county comparison, county vs state vs U.S. bars.
- Sortable, filterable priority table with CSV download.
- Targeting tool: equity-first, balanced (recommended) and reach-first strategies with a budget
  slider, women reached, double-burden coverage, reach chart, map outlines and CSV export.
- Methods, validation, limitations, citation, prevention resources (CDC, HRSA).

## Notes
- Libraries: Leaflet 1.9.4 (unpkg CDN) and Google Fonts. No basemap tiles, so no API key is needed.
- Photos are hotlinked from Unsplash under the Unsplash License: NASA (hero), Bioscience Image
  Library by Fayette Reynolds (epithelium), CDC (vaccination), Jake Blucker (rural road). If an
  image fails to load, a teal gradient shows instead.
- Scores describe counties, not individuals, and are not medical advice. Cancer incidence and
  mortality are shown for context only and were never inputs to the index. Alaska and Hawaii are
  not mapped.
- To change colors, breaks or text, edit `RAMP`, `LAYERS` and `STRATS` near the top of the script
  in `index.html`.
