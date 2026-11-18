# SQL

**Summary**: Notes on SQL and spatial databases such as PostGIS and DuckDB. Related: [[GIS]].
**Last updated**: 2026-11-18

---

- [PostGIS spatial joins in DuckDB (Geomermaids)](https://www.geomermaids.com/cookbook/duckdb-spatial/): Rewrites common PostGIS spatial joins for DuckDB and compares query plans on FEMA flood data. Tips: explicit R-tree indexes, one spatial predicate per join, metric CRS for distance joins, inlined bounding boxes to clip Parquet. See [[GIS]], [[Data]]. *Keywords*: DuckDB, spatial SQL, spatial joins, query optimization, R-tree, PostGIS
- [Introduction to PostGIS](https://postgis.net/workshops/postgis-intro/): Workshop on PostGIS: loading data, spatial SQL, joins, indexing, projections, geography, rasters and database admin. See [[GIS]]. *Keywords*: PostGIS, PostgreSQL, spatial SQL, workshop, spatial index
