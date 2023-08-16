# Calculating Water Surface Occurrence from Remote Sensing Data

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

#### Here we provide the codes used to prepare remote sensing data and perform Random Forests analysis present in Valerio et al., (2023, submitted)

Two GEE codes are present and developed for two public satellites, namely Sentinel-1 and Sentinel-2.
The first GEE code [Data_Extraction] (https://code.earthengine.google.com/e0033f21447392da736fba2ee19ac42a) allows the data extraction from water bodies polygons of spatiotemporally coincident remote sensing information.
The second GEE code [Export_Rasters] (https://code.earthengine.google.com/e0033f21447392da736fba2ee19ac42a) allows exporting remote sening information coincident with water bodies polygons.

The two codes are also present in the GEE directory.
In the R directory is present the R code for replicating the Random Forests classification analyses present in Valerio et al., (2023, submitted). 
We have implemented parallelization techniques, we have effectively divided complex tasks into smaller, manageable units of work that can be executed simultaneously. Our aim was not only to boost performance and reduces execution times, but also enhance code reusability.


[MODIS](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_MODIS) 
