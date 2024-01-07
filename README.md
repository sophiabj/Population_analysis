# Population_analysis

Design Process for Slovakia Population Analysis

Step 1 (Download Data): 
Data for 2006 and 2021 respectively would be downloaded from the source link. https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/population-distribution-demography/geostat 

Step 2 (Load and Clean): Loading and cleaning the data is the foundational step. It ensures that the data is in a usable format and relevant to the analysis. Data cleaning steps include extracting values from shapefiles and rasters as applicable, removing unnecessary columns, and filtering data for Slovakia. 2006 population grid data has a shapefile containing coordinates and a csv file containing population values. 2021 population grid data is available as raster (GeoTIFF) and geopackage (GPKG) containing both coordinates and population values. 

Step 3 (Relative Increase): Calculating the relative increase in population is essential for identifying areas with significant changes. This step adds a new column to the dataset.

Step 4 (Top 5 Cells): Identifying the top 5 cells with the highest relative increase highlights the areas of most interest in the analysis.

Step 5 (Population Stats): Calculating the average and median population for 2021 provides additional insights into the overall population distribution.

