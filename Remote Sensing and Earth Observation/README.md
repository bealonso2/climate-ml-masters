# Remote Sensing and Earth Observation

In this chapter, we explore the fundamental tools and techniques for remote sensing and earth observation. We'll work with both raster and vector data, covering various practical applications relevant to climate and environmental monitoring. These skills are essential for understanding, analyzing, and making informed decisions based on satellite and geospatial data.

As always, you are encouraged to dive deeper wherever you see fit!

## Foundations of Remote Sensing

Remote sensing is the use of satellites or aircraft to observe the Earth's surface. These observations help us measure and monitor features like vegetation health, snow cover, flood events, wildfire activity, and other critical environmental factors.

### Key Concepts

- **Sensor Types**: Different types of sensors capture imagery at different wavelengths, such as optical, infrared, and radar.

- **NDVI (Normalized Difference Vegetation Index)**: This index measures vegetation health by analyzing how plants reflect light at certain wavelengths.

- **NDSI (Normalized Difference Snow Index)**: This index is used to detect snow cover by distinguishing between snow and other materials.

- **Multi-band Imagery**: Imagery that contains multiple layers, each representing different parts of the electromagnetic spectrum.

## Working with Raster Data

Raster data is the most common format for remote sensing imagery, representing the Earth's surface in grids of pixels, each with a value representing a specific property like temperature or reflectance.

### Key Tools and Datasets

- **[Google Earth Engine](https://earthengine.google.com/)**: A powerful tool for working with large satellite datasets like **Landsat**, **Sentinel**, and **MODIS**.
- **Python Libraries**: Tools like **Rasterio** and **Geopandas** make it easy to manipulate and analyze raster data.

## Project: Working with Raster Data to Understand NDVI and NDSI

In the first project, we'll use Google Earth Engine to calculate NDVI and NDSI for a selected region using Landsat imagery. This will provide a hands-on understanding of vegetation health and snow cover analysis.

[Get started here!](./Start/NDVI%20NDSI%20Analysis.ipynb)

## Project: Another Raster Example—Maui Wildfire Analysis

In this project, we'll analyze the extent of a wildfire in Maui using Sentinel-2 imagery. We'll calculate the **Normalized Burn Ratio (NBR)** to identify the burned area. This project will give you a practical understanding of the challenges producing high-quality images for wildfire monitoring.

[Get started here!](./Start/NBR%20Fire%20Analysis.ipynb)

### Project: Landsat and Sentinel Image Analysis

In this project, we'll use **Google Earth Engine** to obtain **Landsat** and **Sentinel** imagery and analyze changes over time, such as deforestation or urban growth. You'll also learn how to work with raster data using Python to calculate relevant metrics like vegetation indices.

[Get started here!](./Start/Raster%20Image%20Analysis.ipynb)

## Vector-Based Spatial Data Analysis

Vector data consists of points, lines, and polygons that represent various features like cities, roads, or power grid infrastructure. Analyzing vector data allows us to make meaningful conclusions about spatial relationships.

### Key Tools

- **GeoPandas**: A Python library for handling and analyzing vector data.
- **QGIS**: A powerful open-source GIS tool for visualizing and processing geospatial data.
- **Shapely**: A Python package for geometric operations like buffering and spatial joins.

### Project: Mapping Emission Sources and Power Grids

In this project, we will use **GeoPandas** and **QGIS** to map emissions sources and power grid infrastructure. The aim is to understand the spatial relationships between different infrastructure components and emission hotspots, with a focus on using **vector-based analysis** to optimize planning and disaster response.

[Get started here!](./Start/Vector%20Analysis%20Emission%20Sources.ipynb)

## Hands-On Challenge: Integrating Raster and Vector Data

Remote sensing is most powerful when we combine raster and vector data to derive insights. For example, combining NDVI (raster) with agricultural field boundaries (vector) can help identify which specific fields are experiencing reduced vegetation health.

### Project: Field-Level Vegetation Monitoring

In this integrated project, we will analyze **vegetation health** across different agricultural fields using **NDVI** from raster data and field boundaries from vector data. Additionally, we will apply machine learning models such as random forests or gradient boosting to predict vegetation health metrics based on spatial and temporal features. This kind of analysis is particularly useful for **precision agriculture**.

[Get started here!](./Start/Field%20Level%20Vegetation%20Monitoring.ipynb)
