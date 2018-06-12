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
- (maybe other tags like safety, speed, confort on scale 0-10 [inspired by](http://wiki.freemap.sk/BicykelPreprocessing))

### contours
- height (of the contour in meters)
- z13: every 100m; z15: every 25m; z17: 10m

### buildings
- building tag
- name

### water
- 

### railway
- railway
- tram

### other
- airports, aeroway

### admin

### POI
