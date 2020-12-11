# Optimizing Marine Protected Areas for Elasmobranchs in Mozambique: Project for 270P at UC Bren School of Enviornmental Science & Management
This repository contains code by: Rachel Rhodes and Vanessa Rathbone

## Content:
* `data`: Contains all raw species disribution data .
* `outputs`: Contains tifs used to create result outputs
* `rasters`: Contains all the tifs created and used during the model runs
* `RMD Files`: RMD files 1-8 should be run in order. RMDs 1-5 are the prep and setup files, RMDs 6-8 run the model once the prep work has been done. Since we have saved the raster done in steps 1-5 in the 'rasters' folder, you can run RMDs 6-8 without needing to do the setup first. 

## Notes:
The systematic conservation prioritization package `prioritizr`used for the spatial prioritization uses the Gurobi library which requires a license. More information about installing Gurobi: https://prioritizr.net/articles/gurobi_installation.html

