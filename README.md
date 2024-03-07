# Calculating Water Surface Occurrence from Remote Sensing Data

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

#### Here we provide the codes used to prepare remote sensing data and perform Random Forests analyses present in Valerio et al., (2023, submitted).

Two GEE codes are present and developed for two public satellites, namely Sentinel-1 and Sentinel-2.

The first GEE code [Data_Extraction](https://code.earthengine.google.com/e0033f21447392da736fba2ee19ac42a) allows the data extraction from water bodies polygons via spatiotemporally coincident remote sensing information.

The second GEE code [Export_Rasters](https://code.earthengine.google.com/e0033f21447392da736fba2ee19ac42a) allows exporting remote sening information overlapping water bodies polygons prior to Random Forests classification analyses.

The two codes are also present in the GEE directory.

In the R directory is present a R code for replicating the Random Forests classification analyses. 
We have implemented parallelization techniques as we have effectively divided complex tasks into smaller, manageable units of work that can be executed simultaneously. 

As such, our aim was not only to boost performance and reduces execution times, but also enhance code reusability.

How to cite this work:

Valerio F, Godinho S, Gonçalo F, Pita R, Gameiro J, Silva B, Marques AT, Silva JP (2024) Multi-Temporal Remote Sensing of Inland Surface Waters: A Fusion of Sentinel-1&2 Data Applied to Small Seasonal Ponds in Semiarid Envir, bioRxiv, 2024.03.03.583180; doi: https://doi.org/10.1101/2024.03.03.583180

