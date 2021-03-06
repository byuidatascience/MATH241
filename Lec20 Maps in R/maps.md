Working With Maps
========================================================
author: Albert Y. Kim
date: Wednesday 2015/03/11





GIS
========================================================
Geographical information system (GIS) is a system designed to capture, store, manipulate, analyze, manage, and present all types of spatial or geographical data.

Typical GIS software include ArcGIS and ArcMap.




GIS
========================================================
At its simplest, geographic elements are

* Points: landmarks
* Lines: roads, coarse representation of a river
* Polygons: geographic areas, lots, etc.


Shapefiles
========================================================
The **shapefile** format is a popular geospatial vector data format for geographic information system (GIS) software. It is developed and regulated by Esri as a (mostly) open specification for data interoperability among Esri and other GIS software products.



Spatial Polygons
========================================================

We're going to import shapefiles into R and convert them into **SpatialPolygons** (sp) objects.  At its simplest, an sp object consists of:

* A plotting order
* A bounding box of the the geographic extent in question
* A coordinate system (latitude/longitude, UTM, NAD) to project a 3D globe onto a 2D page.
* A list of polygons
* Any relevant data to each geographic object

The last three are the most relevant to you.
