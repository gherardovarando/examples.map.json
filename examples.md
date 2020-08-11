* `firenze.map.json`: example of a classical map
with a base layer and numerous vector layers.

* `hippocampus.map.json`, an example of a large non-geographical map showing the hippocampus region of a mouse brain. Automatically detected puncta are visualized with as
a [csvTile](https://github.com/gherardovarando/leaflet-csvtiles), moreover the map supports [leaflet-multilevel](https://github.com/gherardovarando/leaflet-multilevel).

* `hippocampus_slim.map.json`, layer configurations are retrieved from a remote url.

* `italy.map`: an example of how is possible to link external layer configuration files (`layer.json`) from the main map configuration file (`italy.map.json`). Moreover the `region.layer.json` is an example of a configuration for a GeoJSON layer where the GeoJSON data are retrieved from a url.  

* `italy-vector.map.json`: an example of how to build a map using GeoJSON layers. The base layer consists of the boundaries
of the italian regions while the other two layers are the finer administrative subdivisions.

* `north_italy_1828.map.json`: a simple map from an image.
   The alignment with EPSG3857 has been done visually as
   example. 

* `neurons.map.json`: a non-geographical example of a multi-level map using [leaflet-multilevel](https://github.com/gherardovarando/leaflet-multilevel).

* `stars.map.json`: an example of a non-geographical map where points are showed using the [leaflet-csvtiles](https://github.com/gherardovarando/leaflet-csvtiles) plugin.

* `world-vecto.map.json`: a simple world map using GeoJSON data.
