# EDS220: Homework Assignment 4- Spatial Cover of the January 2025 Southern California Wildfires
Author: Nathalie Bonnet

## About
This repository houses the data wrangling and analysis used to produce true and false color images of the Los Angeles County area and a map of where the January 2025 Eaton and Palisades fires burned. Analysis contained exploration and manipulation of historical fire data from LA County and a Landsat NetCDF file. 

## Repository structure
**.gitignore**: git ignore contains instructions what files and folders the IDE should not track. The fire perimeter for this repository is contained in the gitignore to reduce runtime issues. 

**README.md**: setup instructions.

**hw4-task2-false-color-BONNET.ipynb**: the Jupyter notebook containing all data processing and outputs of analysis. 

**landsat88-2025-02-23-palisades-eaton.nc**: NetCDF file that was transferred to be used remotely and locally within the repository

## Data
All data used was publicly available though the California State Geoportal and Landsat Collection 2 data from the Landsat 8 satellite. The California wildfire perimeter data is available as a CSV and a geodatabase through the website download link. Landsat data is available as a NetCDF dataset. The geopandas, xarray, and rioxarray libraries were used to load and manipulate the data files in python. 

## References
Landsat 8 Satellite Data: Planetary Computer. Microsoft Planetary Computer. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Fire Perimeter Data: California State Geoportal. California Historical Fire Perimeters [Dataset]. https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-historical-fire-perimeters/explore?layer=2&location=37.338129%2C-119.269051%2C6.09&showTable=true
