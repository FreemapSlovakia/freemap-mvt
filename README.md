# freemap-mvt
support for mvt files in freemap project

## TODO
- frontend, stylesheets ([Leaflet plugins](https://leafletjs.com/plugins.html#vector-tiles), [more demos](https://openmaptiles.org/docs/website/leaflet/) )
- mvt backend

## Layers

### background
- landuse
- leisure
- name

### bicycle
- highway (type)
- name (of the highway)
- cycleroute (info about highest ranking `roude=bicycle` on this highway; values: icn, rcn, lcn)
- ref (refs of all bicycle routes, or just the highest ranking?)
- surface

### contours
- height (of the contour in meters)

### buildings
- building
- name
