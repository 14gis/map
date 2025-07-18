# 14gis-map

**Frontend map viewer for the 14gis platform.**  
Displays, explores and interacts with geospatial layers provided by the 14gis-core backend.

## Purpose

- Interactive map interface (planned: OpenLayers, MapLibre)
- Layer toggle, attribution, scoring overlays
- Responsive, accessible UI for exploration and evaluation
- Prepared for integration with `14gis-core` API

## Tech Stack (suggested)

- JavaScript / TypeScript
- Framework: React or Vanilla
- Map Engine: OpenLayers (existing) or MapLibre
- Optional: Tailwind CSS, Vite, Leaflet

## Structure (planned)

```
/public           → Static assets
/src
  /components     → Reusable UI parts (LayerSwitcher, Legend, etc.)
  /views          → Main views/pages
  /api            → Integration with 14gis-core
  /styles         → Styling, themes
README.md
.gitignore
package.json
```

## Setup (coming soon)

Installation guide and dev setup will be provided after framework selection.

## Part of the 14gis system

Built and maintained under the [14gis](https://github.com/14gis) project,  
powered by [14co.de](https://14co.de).
