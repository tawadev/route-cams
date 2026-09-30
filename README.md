# Route Cams

Enter a From and To address and watch the live TxDOT traffic cameras along the route, in driving order.

- Camera list and live streams: the service behind [drivetexas.org](https://drivetexas.org) (not an official public API; it may change without notice)
- Address suggestions and checking: Esri ArcGIS World Geocoder
- Routing: OSRM public demo server
- Map: Leaflet + OpenStreetMap

It's a single static page (`index.html`) with no build step. To run it locally:

```
python -m http.server 8765
```

Then open http://localhost:8765.

# Watch Live
https://tawadev.github.io/route-cams/
