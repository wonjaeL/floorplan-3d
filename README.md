# floorplan-3d

A simple Three.js 3D viewer for a Korean studio loft (복층 원룸) reconstructed from a 2D floor plan and reference photos.

**Live demo:** https://wonjael.github.io/floorplan-3d/

## Controls

- Left-drag: orbit
- Mouse wheel: zoom
- Right-drag: pan
- Buttons: preset views (iso / top / front / inside), toggle roof and loft

## Layout

Approximate dimensions used for the model:

- Footprint: 5.6 m × 3.0 m
- 1F ceiling: 2.2 m
- Total height (incl. loft): 4.0 m

1F: bed, sofa + side table, kitchen counter (induction / sink / washing machine / fridge), bathroom, wood staircase.
Loft: mezzanine floor over kitchen + bathroom, white guardrail, grid storage shelves, mattress.

## Run locally

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8765
# http://localhost:8765/
```

No build step. Uses Three.js from CDN via importmap.
