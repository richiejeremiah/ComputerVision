# Project Overview and Objectives

The main purpose of this project was to use computer vision to detect brain tumors in MRI Scans. In order to do this the scans were annotated using the VGG Image Annotator and the a deep learning model was developed using the Mask R-CNN model architechture. The dataset containted few images hence this project didn't focus on model accuracy as it was clear that the model would not have performed well due to small dataset however this project shows how to build such model.

Mask R-CNN is an object detection model based on deep convolutional neural networks (CNN) developed by a group of Facebook AI researchers in 2017. The model can return both the bounding box and a mask for each detected object in an image.

This project covers the following:


* Preparing the Model Configuration Parameters
* Building the Mask R-CNN Model Architecture
* Loading the Model Weights
* Reading an Input Image
* Detecting Objects
* Visualizing the Results
* Complete Code for Prediction
* Downloading the Training Dataset
* Preparing the Training Dataset
* Preparing Model Configuration
* Training Mask R-CNN in TensorFlow 1.13
* Conclusion
