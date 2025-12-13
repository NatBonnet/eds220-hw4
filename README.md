# EDS220: Spatial and Socioeconomic Impacts of the January 2025 Southern California Wildfires
Author: Nathalie Bonnet
Instructors: Dr. Carmen Galaz García and Annie Adams

## About
This repository houses two notebooks used to create a personal website blog post exploring the spatial and socioeconomic impacts of the Los Angeles County 2025 wildfires. Three data sources were used to conduct analyses. California Historic Fire Perimeters data were used for both seperate analyses. Landsat satellite data explored true and false color imagery to map where the January 2025 Eaton and Palisades fires burned. EJI (Environmental Justice Index) data were used to explore the socioeconomic factors that might play into fire recovery. All data exoloration, analysis, and preliminary outputs seperate datasets are contained in their respective repositories. The significant aspects of each analysis were adapted to a seperate worflow to connect spatial and socioeconomic impacts in the final blog post: [Visualizing the 2025 Southern California Wildfires]( https://natbonnet.github.io/posts/la_fires/la_fires.html)

## Repository structure
```
eds220-phoenix-biodiversity
│   README.md
|   los-angeles-fires-eji.ipynb
|   los-angeles-fires-landsat.ipynb
|   .gitignore
    │
    └── data 
```
**.gitignore**: git ignore contains instructions what files and folders the IDE should not track. Data from fire perimeters and lansat NetCDF are contained by the gitignore in the data folder.

**README.md**: setup instructions.

**los-angeles-fires-eji.ipynb**: the Jupyter notebook containing analyses using EJI 2024 geodata.

**los-angeles-fires-landsat.ipynb**: The Jupyter notebook containing analyses using Landsat 8 satellite image data.

## Data
All data used was publicly available though the California State Geoportal, Landsat Collection 2 data from the Landsat 8 satellite, and the 2024 EJI download from the Centers for Disease Control and Prevention Agency for Toxic Substances and Disease Registry. The California wildfire perimeter data is available as a CSV and a geodatabase through the website download link. Landsat data is available as a NetCDF dataset. EJI data was accessed as a Geodatabase.

## References
Landsat 8 Satellite Data: Planetary Computer. Microsoft Planetary Computer [Data Collection]. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Fire Perimeter Data: California State Geoportal. California Historical Fire Perimeters [Dataset]. https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-historical-fire-perimeters/explore?layer=2&location=37.338129%2C-119.269051%2C6.09&showTable=true

Centers for Disease Control and Prevention and Agency for Toxic Substances Disease Registry. 2024 Environmental Justice Index [Dataset]. https://atsdr.cdc.gov/place-health/php/eji/eji-data-download.html
