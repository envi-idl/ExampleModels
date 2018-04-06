# ExampleModels

A collection of example models generated with the ENVI Modeler.

Note that you will not be able to run every model that is included because you will not have the data. However, it is easy to replace/update the input data nodes with your own data to try them on your own.

## Requirements

In order to run these models, you will need **ENVI 5.5** or newer.

## Models

Here is a list and short description of the included models:

- **ACE Target Detection**: This is a map of the McCaslin and US-36 interchange. Actually it runs ACE target detection analysis, using the mean and covariance from subspace background statistics. Brighter pixels represent a close match to the "Dry Grass" spectrum in the veg_2grn.sli spectral library. 

- **Automatic Image Registration**: Simple model that demonstrates how to perform image-image registration.

- **Comparing Classification Methods**: Nice model that compares four different classification methods on a single raster and ENVI ROI. 

- **Find Minerals**: Example that demonstrates how to map minerals in a hyperspectral image using ENVI's hyperspectral tools. Alunite and Kaolinite are mapped in this example. 

- **Generate Contour Lines**: This simple example generates contour lines on a raster using ISODATAClassification and is an example of how you can use algorithms in ENVI for different applications.

- **Hillshade Image**: This model takes a DEM and creates an image where color shows elevation and shading represents terrain shape.

- **Image Change with Spectral Index**: This model follows the Image Change workflow and uses a spectral index as the metric to quantify change.

- **Iterate over number of classes**: Automtatically run ISODATA classification with 3,6, and 9 classes and visualize the results. Shows how the Iterator node works in the modeler. 

- **NDVI on Raster Series**: Example processing every raster in a raster series.

- **Nested Loop Example**: Comparing all the bands in a raster file against themselves. This requires nested looping, an advanced feature that is achieved using metatasks.

- **Pan Sharpening Comparison**: Compares the different PanSharpening algorithms available in ENVI

- **Pan Sharpening Iterator**: Shows how to use one Iterator node to process two arrays of rasters to perform NNDiffusePanSharpening on all rasters.

- **Raster Stacking**: Demonstrates how to stack an array of rasters if they have overlap.

- **SAM Image Difference**: Uses a new ENVI Task called "SAM Image Difference" to perform change detection. SAM = Spectral Angle Mapper. Note that, if you use this, you will want to register your images to one another if they are not already as this is a pixel-based change detection algorithm.

- **Softmax Classification Framework**: An example showing how to use the Softmax classification algorithm in ENVI with the new classification framework.

- **Supervised Classification - Batch**: An example showing how to perform supervised classification on many images using training data from one image.

- **SVM Classification Framework**: An example showing how to use the SVM classification algorithm in ENVI with the new classification framework.


## License

Licensed under MIT. See LICENSE.txt for additional details and information.

Copyright (c) 2018, Harris Geospatial Solutions, Inc.
