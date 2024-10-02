# Enhancing Satellite Image Composite using Temporal Proximity for Deep Learning-based Cropland Segmentation
This repository contains the implementation of a Deep Learning-based cropland segmentation task utilizing Sentinel-2 time series composite imagery. The composite images are generated using a novel method that integrates cloud-shadow masking and temporal proximity, specifically designed to enhance the accuracy of cropland segmentation across multiple regions. The approach is tailored to maintain phenological continuity and ensure robust segmentation performance under varying environmental conditions. The code is developed in conjunction with a research article that evaluates the effectiveness of different compositing methods, including the proposed technique, in diverse agricultural settings.


How to Use:
Composite Generation:
Open the Google Earth Engine script at this link:
https://code.earthengine.google.com
and modify the region of interest and time period based on your study area.
Generate the composite image using the provided script. Output imagery will be saved as a GeoTIFF in your designated GEE folder.
Running the Notebook:

Download the provided Jupyter notebook: CropClass_CompareGEEcomposite_T15SXU_Github.ipynb.
Install necessary dependencies such as TensorFlow, Keras, and rasterio if not already installed.
Load the Sentinel-2 composite image generated from GEE into the notebook, and configure the file paths for training data.
Deep Learning Model:

Use the notebook to train a deep learning model for cropland segmentation. The model architecture can be customized within the notebook.
Evaluate the segmentation accuracy based on different composite methods, including the proposed one.
Comparison of Results:

The notebook also provides a comparison between the proposed compositing method and other standard techniques by generating segmentation maps and computing performance metrics like F1-scores and accuracy.
