# Hands-on Map — Miami

This small project gives you a hands-on map you can use interactively (on a laptop/tablet) and print for physical, tactile activities.

Files:
- `index.html` — interactive Leaflet map centered on Miami. Open it in a browser (double-click or serve with a local static server).
- `data/miami-points.geojson` — sample points/landmarks.

How to use (interactive):
1. Open `index.html` in a web browser (Chrome, Firefox).
2. Drag markers to plan activities. Use the Toggle Grid button to overlay a latitude/longitude grid (step ~0.02° — adjust in the code).
3. Click Print to save as PDF or print on paper.

How to create a printed, tactile "hands-on" map:
Materials:
- Printed map on heavy cardstock (160–300 gsm) or print on regular paper and glue to cardboard.
- Puffy fabric paint, hot glue, or silicone caulk (for raised roads/coastlines).
- Yarn or string (for routes and boundaries).
- Textured papers or sandpaper (for parks, beaches, water).
- Stickers or marker stickers for landmarks.
- Laminator (optional) — makes a durable surface to put Velcro pieces or reuse with dry-erase markers.

Simple tactile feature ideas:
- Coastline: trace coastline with puffy fabric paint (let dry) so it becomes raised.
- Roads / Transit: glue yarn for main roads or transit lines.
- Parks: glue green felt or sandpaper for different texture.
- Water: use glossy varnish or cellophane strips.
- Airport / Important buildings: small foam stickers or LEGO bricks glued in place.
- Grid: print the grid using the map grid option and punch small holes on grid intersections for counting activities.

Activity ideas:
- Grid-navigation: give children coordinates (grid squares) and ask them to place a sticker at that coordinate.
- Route planning: use yarn to create a route from airport to a landmark, count grid squares or distance.
- Scavenger hunt: create cards like “Find Wynwood, place a yellow sticker” or “Trace the route for emergency vehicles from MIA to Downtown.”
- Elevation simulation: use layered cardboard to represent higher ground if desired.
- Accessibility exercise: mark accessible entrances, plan routes avoiding stairs (use tactile cues).

Customization notes:
- To change grid spacing, edit `gridStep` in `index.html` (value is in degrees).
- Add more GeoJSON features to `data/miami-points.geojson` and extend the marker rendering in `index.html`.
- If you want a printable high-resolution map without tile attribution, consider using a static map export tool (Mapbox Static Maps, or export tiles) while respecting tile provider TOS.

If you want, I can:
- Add more landmarks or school-specific POIs to the GeoJSON.
- Create a printable PDF layout (A4/Letter) pre-configured with grid and legend.
- Add an interactive legend allowing toggling categories (parks, transport, museums).
- Create a tactile map template (black & white with simple outlines) optimized for printing and tracing for raised-paint production.

Tell me which of the above you want next (PDF printable template, more POIs added, or I can open a PR to add these files to your repo).
