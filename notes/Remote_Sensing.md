# Remote Sensing

**Summary**: Notes on satellite and aerial imagery, Earth observation data products, and how they are analyzed and distributed.
**Last updated**: 2026-11-18

---

- [Stop using satellite LST to quantify heat hazard (LinkedIn post)](https://www.linkedin.com/feed/update/urn:li:activity:7478690057026207745/): TC Chakraborty argues that satellite land surface temperature (LST) measures the radiometric "skin" temperature of roofs, roads and tree canopies, not the air people feel. The post says LST maps overstate [[Climate_Change]] heat hazard and the cooling benefit of trees, and that this erodes trust in the science. Replies discuss LST's value in data-scarce regions and the relevance of radiant heat in [[Urban_Planning]].
  **Keywords**: land surface temperature, LST, air temperature, extreme heat, urban heat island, science communication

- [The Technical Debt of Earth Embedding Products](https://cloudnativegeo.org/blog/2026/02/the-technical-debt-of-earth-embedding-products/): Isaac Corley (CNG blog, Feb 2026) compares nine Earth [[Embeddings]] products, including AlphaEarth, Clay, Tessera, Presto and Major TOM, by resolution, dimensions, dtype, license and storage cost. The post argues that inconsistent formats, grids and CRS handling hold back their use more than model quality does, and recommends cloud-native formats (GeoParquet, COG, Zarr) with benchmarks and provenance. See also [[Data]].
  **Keywords**: earth embeddings, foundation models, AlphaEarth, GeoParquet, cloud-native geospatial, interoperability

## Related

- [[Agriculture]]: agribound, a field boundary delineation toolkit for satellite imagery
