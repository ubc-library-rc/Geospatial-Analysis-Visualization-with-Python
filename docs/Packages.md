---
layout: default
title: Geospatail Analysis
nav_order: 3
---

# Geospatial Analysis

For working with vector data, [geopandas](https://geopandas.org/) is one of your best options.  It is a spatial extension for pandas, the package for handling tabular data we just worked with. **Working with Geopandas.ipynb**" will give you an overview of:

* Importing a Shapefile
* Editing and Viewing Data
* Changing Coordinate Reference Systems
* Spatial Overlay
	* Clip
* Normalize Data
	* Calculate Population Density
* Writing data
	* Shapefiles - limitations and workarounds
	* Geojson - flexible but bulkier alternative

# An Applied Example

"**Analyzing Police Violence with Python.ipynb**" will build on these skills and apply them to a very important issue.  You will

* Import Point Data
	* Read a .csv file
	* Project Latitude/Longitude Data 
* Importing a GeoJson
* Spatial Overlay
	* Spatial Join
	* Point in Polygon
* Normalize Data
	* Death Rate
* Calculate Kernel Density
* Save Raster Layer