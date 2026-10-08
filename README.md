# Launglon landslides 2026: drone tile sets

Web-map tiles (512 px WebP, XYZ scheme; Leaflet `tileSize: 512, zoomOffset: -1`) for the dashboard at
https://geonet-myanmar.github.io/launglon-landslides-2026/, hosted separately so that site stays under GitHub Pages'
1 GB limit.

| folder | survey | resolution |
|---|---|---|
| `zalut/` | Pyin Gyi - Za Lut, Launglon Township, flown 7 Oct 2026 (two flights merged) | 9.7 cm, tiles z13-z20 |
| `rabe/` | Ra Be - Kyauk Twin road, Launglon Township, flown 8 Oct 2026 (two flights merged) | 9.2 cm, tiles z13-z20 |

Built by `scripts/10_tiles.py zalut|rabe` in the `launglon-landslides-2026` repo; do not edit by hand.
