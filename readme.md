### How to

* Pick your points of interest into a `.geojson` file.  The a Point collection would look like this structure

```
{"type": "FeatureCollection", "features": [

  {"type":"Feature",
    "properties":{"name":"text"},"geometry":{"type":"Point","coordinates":[0.1, 2.3]}
  },

  {"type":"Feature",
    "properties":{"name":"texts"},"geometry":{"type":"Point","coordinates":[4.5, 6.7]}
  }

]}
```

* Test your `.geojson` file using [GeoJson.io](http://geojson.io) or [geojsonio-cli](https://github.com/mapbox/geojsonio-cli)
* The geojsonio-cli will validate your json to make sure it is valid
```
$  geojsonio poi.geojson
```
