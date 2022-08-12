# Exploring AVIRIS-NG Surface Reflectance

**Author:** ORNL DAAC
**Date:** August 14, 2022
**Contact for the ORNL DAAC:** uso@daac.ornl.gov

**Keywords:** ORNL DAAC, AVIRIS-NG, ABoVE, Python

## Tutorial Overview
This tutorial demonstrates methods to read and perform a Principal Components Analysis on 1 file of Surface Reflectance data from the AVIRIS-NG instrument. The AVIRIS-NG (Airborne Visible/Infrared Imaging Spectrometer-Next Generation) instrument provides continuous radiance measurements of surface reflectance. This approximates one step in a study of Wetland Vegetation Classification conducted by NASA's Arctic-Boreal Vulnerability Experiment (ABoVE) Science team. The study incorporated data from NASA airborne instruments, including the AVIRIS-NG instrument. The ABoVE study included applications associating spectral characteristics with land cover classification focused on water and wetland vegetation communities over the Peace-Athabasca Delta (PAD), Canada.

In this tutorial, we'll use python methods to:

- Read and explore a flight path of AVIRIS-NG Spectral Reflectance (L2) data
- Create Spectral Profiles of the AVIRIS-NG data
- Export georeferenced multiband geoTIFF files
- Run a Principal Components Analysis (PCA) on an AVIRIS-NG Spectral Reflectance file

<img src="images\aviris-ngRGB.PNG" width="200" style="display:block;margin-left: auto; margin-right:auto;">

## Procedure

Links to Notebooks:

Jupyter Notebook: [ESA2022_ABoVE_AVIRIS-NG_Notebook.ipynb](ESA2022_ABoVE_AVIRIS-NG_Notebook.ipynb)  

## Related Tutorials
More tutorials related to ORNL DAAC data and web services can be found at the [ORNL DAAC Learning](https://daac.ornl.gov/resources/learning/) page.
