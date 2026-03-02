### 4. Landslide Susceptibility Assessment  
Upper Marikina River Basin Protected Landscape (UMRBPL), Philippines

Developed a GIS-based landslide susceptibility model using multi-criteria evaluation to identify high-risk zones within the Upper Marikina River Basin Protected Landscape.

This project integrated terrain, environmental, and proximity-based factors to generate a weighted susceptibility map for hazard assessment and planning support.

---

#### Input Factors

- Slope (derived from DEM)
- Elevation
- Land Use / Land Cover (LULC)
- Soil Type
- Distance to Rivers
- Rainfall
- Typhoon Intensity

---

#### Methodology

1. Generated slope and elevation rasters from DEM.
2. Reclassified each factor into susceptibility classes.
3. Standardized raster layers to a common scale.
4. Assigned weights to each factor using a weighted overlay approach.
5. Performed raster overlay analysis to compute final susceptibility index.
6. Classified output into:
   - Very Low
   - Low
   - Moderate
   - High
   - Very High susceptibility zones

---

#### Output

- Landslide Susceptibility Map
- Area statistics per susceptibility class

---

#### Tools Used

- QGIS (Raster Calculator, Reclassification, Weighted Overlay)
- Multi-Criteria Decision Analysis (MCDA)
