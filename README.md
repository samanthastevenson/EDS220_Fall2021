# EDS220_Fall2021

Welcome to EDS 220, Fall 2021! This is the master repository for all example course materials, which will be added to throughout the course of the quarter. As we progress, parts of this repo will be cloned into smaller repo's for course assignments via Github Classrooms, but this should serve as a useful reference for us all.

You are welcome to copy these materials, make your own changes, and even fork this repository if you like! If you find that the changes you made could be useful to others, please also feel free to submit pull requests so they can be incorporated into the course for future students.

#### Setup: Before Starting These Notebooks 
Make sure to check out these instructions for downloading/installing Anaconda, Jupyter, and the Google Earth Engine environment (and activating the GEE environment).
https://docs.google.com/document/d/1P1c6Ef7D1OoGaTaOrPDO0m5LBN1okpGlU0OXKKzsoi0/edit

## Description of materials

These notebooks provide an introduction to various environmental data sets, which should give you a good sense of the range of tools out there for manipulating and processing environmental data as well as the types of data sets that exist. 

### GEE_Setup: Configuring Your Computer and Python Environments
This notebook just contains some basics on setting up Jupyter on your local machine, creating a custom environment for Google Earth Engine (GEE), and making a blank map. There is substantial overlap with the next notebook, this is just here to provide some extra assistance with the initial setup.

### Week1_ERA5Maps_GEE: Google Earth Engine Intro and Visualization Basics
The first exercise (Week1_ERA5Maps_GEE) provides an overview of how to install the Google Earth Engine Python API and use simple commands to visualize global precipitation data. This will allow you to map information from a global "reanalysis" (= estimate of precipitation everywhere on Earth, derived by using a numerical model that incorporates all available observational data) and display any region you think is interesting!

### Landsat_NDVI_GEE: Using GEE to Derive Indices from Multispectral Data
We continue working in the GEE environment for a more complex example: loading in "multispectral" data (radiation sensed at multiple wavelengths) from the Landsat 8 mission. This example will show you where to find and how to load Landsat data, and use it to calculate a commonly used index for vegetation growth: the Normalized Difference Vegetation Index, or NDVI.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/samanthastevenson/EDS220_Fall2021/main)
