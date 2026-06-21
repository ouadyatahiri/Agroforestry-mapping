# Agroforestry-mapping using high-resolution land use and land cover data
This code aims to combine a very high-resolution tree canopy map (1 m resolution) with a set of land use and land cover maps in order to evaluate their accuracy for agroforestry mapping. The best combination will subsequently be used to estimate agroforestry extent in Europe and the Sahel.
This project aims to refine previous estimations of agroforestry extent at a large scale by moving from a coarse-resolution to a tree-centric approach, as agroforestry systems are sparse and not detectable through 10 and 30 m resolution satellite data. Using higher-resolution data reveals the actual extent of trees on farms.

This project contains two files:
 - LULC_Maps_Overlays.ipynb: Overlays a set of high-resolution land use and land cover data to create agroforestry tree maps and then tests them systematically using large-scale georeferenced validation data.
 - TreeCoverAggregation.ipynb: Aggregates the best-performing agroforestry tree map into 30 m × 30 m resolution to characterize tree canopy cover under agroforestry systems and estimate the extent of agroforestry at large scales.

N.B.: This code is reproducible for any region and time scale. By changing the 'ROI' variable and updating the land use data, users can produce up-to-date and scalable agroforestry maps.
# Required packages 
- [Google Earth Engine API package](https://pypi.org/project/earthengine-api/)
- [Geemap package for visualisation ](https://pypi.org/project/geemap/)
