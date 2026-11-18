# SQL

**Summary**: Notes on SQL databases and query engines, including spatial SQL in PostGIS and DuckDB.
**Last updated**: 2026-11-18

---

- [PostGIS spatial joins, translated to DuckDB](https://www.geomermaids.com/cookbook/duckdb-spatial/): A Geomermaids cookbook for optimizing DuckDB Spatial queries, benchmarked against PostGIS on FEMA flood-zone polygons. Tips include knowing that RTREE indexes don't help joins, using one spatial predicate per join, reprojecting to a metric CRS before ST_DWithin, and buffer-bounded nearest-neighbor search.
  **Keywords**: DuckDB, spatial SQL, PostGIS, spatial joins, RTREE index, query optimization
