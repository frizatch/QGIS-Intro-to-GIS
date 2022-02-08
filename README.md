# Introducing GIS with the opensource software QGIS
<img src="images/qgis-logo_2019.png" width="150"/>

QGIS is an opensource GIS desktop software compatible with mac, PC and Linux systems.

You can be part of the community at [qgis.org](https://qgis.org/en/site/)!

## Workshop Resources
 - Software - access via the [QGIS download page](https://qgis.org/en/site/forusers/download.html)
 - Data - 

## Workshop Goals
By the end of this workshop, you will be able to:
- Explain why spatial information can be important
- Describe vector and raster geospatial data
- Load data into QGIS
- Symbolize ...
- Create a basic map!

## Workshop Sections
- [What is GIS?](#what-is-gis)
- Why QGIS?
- Data types
- The QGIS Interface
- Loading Data
- Symbology
- Classifying Data
- Adding a Basemap - Plugins
- Making a Print Layout


## What is GIS?
And more importantly, why might we want to use it?

GIS stands for either Geographic Information System or Geographic Information Science.

"Geographic Information System" typically refers to the software, like QGIS, we use to create spatial data and to investigate spatial relationships between that data.

"Geographic Information Science" is the framework we use to ask questions about the spatial relationship between data. This framework is broader than working within certain GIS-specific softwares like QGIS. You will also hear people use the phrase "Geospatial Science."

Why is location information important? The knowlege gained by spatial data enhances our understanding.

For example, we may assume that our friend who lives in the city/county of Denver has easy access to a LOT of good restaurants because we know the county has many. But when we map out that most restaurants are downtown and realize our friend lives way out by Denver International Airport, we have a different perspective:

<p align="center">
<img src="images/DenverDIA.png" width="700"/>
</p>

In addition, humans are largely visual. We respond well to seeing information presented in graphs and maps. By using GIS software, we can share our message quickly by *carefully* presenting it in the form of a map. In the above example, we could spend some time explaining that Denver has an odd stretched out boundary to accommodate placing the airport out east. Or we can just **show** it to get the idea across. (*How* we show our data on a map will change our message, but that's for a different workshop.)

Take a moment and think about a particular instance in your life or work where spatial information changes how you think about the situation.

## Why QGIS?

QGIS is an open source, community-driven desktop GIS software that allows users to visualize and analyze spatial data in a variety of ways. There are many reasons to use QGIS, but here are a few:

- It's a robust, powerful desktop GIS
- Runs on all major platorms: Mac, Linux, & Windows
- Free of charge, all access (no paid add-ons or extensions)
- Frequent updates & bug fixes
- Responsive, enthusiastic community
- Integration with other geospatial tools & programming languages like R, Python, & PostGIS
- Access to analysis tools from other established software like GRASS and SAGA
- Native access to open data formats like geoJSON & GeoPackage
- Comes in more than 40 languages, making it easier to work with a larger variety of colaborators
- Growing use by local, state, federal, and international governments

## Data Types

Geospatial data can come in many file types and forms. The two main styles of data you'll encounter are vector and raster data.

image image

### Vector Data
Vector data represents discrete objects in the real world with points, lines, and polygons.

EXAMPLE

Depending on the scale of your map - that is, how much you're zoomed in - one object could have different representations. For example, if a map is of just one farm, the barn might be a rectangular polygon, but if the map is of an entire agricultural valley, the barn might be shown as a single point.

### Raster Data
Raster data stores information in a grid. It is ideal for 

Digital photos are raster data you are already familiar with. If you zoom in far enough on a digital photo, you'll see that photo is made up of pixels, which appear as colored squares. Pixels are cells in a regular grid and each contains the digital code that corresponds to the color that should be displayed there. Satellite images are a very similar situation.
