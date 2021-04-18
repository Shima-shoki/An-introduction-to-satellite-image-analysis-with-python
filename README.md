# An-introduction-to-satellite-image-analysis-with-python
This is a collection of tutorials of satellite image analysis with python. 
The contents are:
## Introduction 1: 
- Python basics
## Introduction 2:
- How to understand the metadata of the satellite images
- How to read band images as numpy arrays
- How to show a satellite image with arbitrary combination of bands
- How to calculate NDVI values
- How to write a geotiff file
## Introduction 3:
- How to clip an image by a rectangular shape of ROI
- How to resample an image to a target resolution
- How to calculate and create a PCA image
## Introduction 4:
- How to read multiple satellite images
- How to specify the location on a numpy array from a geographic coordinate of a point.
- How to show a time-series change of NDVI at a specific location

The satellite images are too large to upload, so I added a code for the google earth engine (GEE) to download sentinel-2 images as geotiff files that are used in the tutorial. Please kindly modify some of the parameters in the GEE download code to find the target images you're looking for.
