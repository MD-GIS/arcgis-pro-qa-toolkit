# Notices and attributions

This project is released under the MIT License (see [LICENSE](LICENSE)).

## Third-party code in the shipped toolboxes

**None.** The toolboxes in `toolboxes/` contain no code copied or adapted from other projects. They import only:

- `arcpy`, which comes with ArcGIS Pro and is not distributed here;
- the Python standard library;
- `openpyxl` (MIT License), optionally, for Excel reports and `.xlsx` input. It ships with ArcGIS Pro and is not distributed here. Without it, reports are written as CSV.


## Published algorithms

These algorithms were implemented from their published descriptions. No code was copied from any implementation. They are credited here as a courtesy:

- **Pole of inaccessibility** (used for interior points of polygons): the "polylabel" method described by Vladimir Agafonkin (Mapbox blog, 2016).
- **Transverse Mercator** for per-feature measuring of wide geographic data: Krueger's series to order n^6 as given by C. F. F. Karney, "Transverse Mercator with an accuracy of a few nanometers", Journal of Geodesy 85 (2011).
- **Polar stereographic** for per-feature measuring near the poles: the ellipsoidal formulas of J. P. Snyder, "Map Projections: A Working Manual", USGS Professional Paper 1395 (1987).

## Trademarks

ArcGIS and ArcGIS Pro are trademarks of Esri. This project is independent and is not affiliated with or endorsed by Esri.
