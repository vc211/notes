# GIS

**Summary**: Notes on GIS software, courses and tools. Related: [[Cartography]], [[Python]], [[SQL]].
**Last updated**: 2026-11-18

---

- [PostGIS spatial joins in DuckDB (Geomermaids)](https://www.geomermaids.com/cookbook/duckdb-spatial/): Rewrites common PostGIS spatial joins for DuckDB and compares query plans on FEMA flood data. Tips: explicit R-tree indexes, one spatial predicate per join, metric CRS for distance joins, inlined bounding boxes to clip Parquet. Main topic: [[SQL]]. See also [[Data]]. *Keywords*: DuckDB, spatial SQL, spatial joins, query optimization, R-tree, PostGIS
- [Course: QGIS for Precision Agriculture (OCWGIS)](https://courses.gisopencourseware.org/course/view.php?id=56): Free course on using QGIS for precision farming: open data, zonal statistics, field data collection with Mergin Maps and drone image processing with WebODM. Main topic: [[Agriculture]]. See also [[Remote_Sensing]]. *Keywords*: QGIS, precision agriculture, drones, WebODM, course
- [Creating a Block World Map (QGIS3)](https://www.qgistutorials.com/en/docs/3/block_world_styling.html): QGIS tutorial that turns a hex grid of elevation data into a 2.5D block map using expressions and color ramps, with DEM data from OpenTopography. Main topic: [[Cartography]]. *Keywords*: QGIS, 2.5D map, hex grid, elevation, map styling
- [Introduction to GIS Programming (Qiusheng Wu)](https://geog-312.gishub.org/book/about/syllabus.html): Free course covering Python basics and geospatial libraries such as GeoPandas, Rasterio, Xarray and Leafmap. Also: [software overview](https://geog-312.gishub.org/book/software/overview.html), [YouTube lectures (Fall 2024)](https://www.youtube.com/playlist?list=PLAxJ4-o7ZoPfb18kNe2luWX9xKg1233i9). See [[Python]]. *Keywords*: GIS programming, Python, GeoPandas, Leafmap, course
- [Introduction to PostGIS](https://postgis.net/workshops/postgis-intro/): Workshop on PostGIS: loading data, spatial SQL, joins, indexing, projections, geography, rasters and database admin. Main topic: [[SQL]]. *Keywords*: PostGIS, PostgreSQL, spatial SQL, workshop, spatial index
- [RustGIS](https://web.rustgis.app/): Browser-based GIS web app, available hosted or as a self-hostable static build. *Keywords*: GIS, web app, browser, Rust
