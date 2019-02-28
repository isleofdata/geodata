These notebooks provide a set of recipes for grabbing and working with geodata, sourced from national and international geodatasets, that is relevant to the Isle of Wight.

The recipes should work for other local authority / council areas if suitable keys are chosen.

The recipes are based around the model of:

- getting shapefiles and location data into a spatialite database
- publishing the spatialite database as a service via a local datasette API
- querying and rendering the data.

Demos are runnable via MyBinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/isleofdata/geodata/master?filepath=notebooks)

The notebooks include:

- *Loading GeoJSON Files into Spatialite*: how to load GeoJson boundary files into a spatialite database
- *spatialite-datasette-demo*: loading Ordnance Survey Boundary-Line data into spatialite then accessing it via a datasette API
- *datasette_spatialite_geoquery*: examples of searching for locations of establishments rated by the UK Food Standards Agency within areas identified by Ordnance Survey Boundary Lines;
- *osmnx-demo*: examples of using OSMNX to query OpenStreetMap to retrieve and render OSM roads and buildings data;
- *geocodes*: simple lookup of ONS geocodes (name, code); still to do: lookups (eg wards in constituency)
