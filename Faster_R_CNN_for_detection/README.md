# Faster R-CNN for Detection

This directory contains the files and utilities necessary for bottle detection using Faster R-CNN.

## Files Description

- **data_preprocessing_faster_rcnn**: Contains script for preprocessing data in preparation for training the Faster R-CNN model.
  
- **faster_rcnn_utils**: Utility functions and scripts that support the Faster R-CNN model's functionalities.
  
- **train_faster_rcnn**: Scripts and functions for training the Faster R-CNN model on the prepared data from Open Image dataset.
  
- **test_faster_rcnn_and_prepare_unet_data**: Contains the Scripts to test the trained Faster R-CNN model and also to prepare the data for fine-tuning the U-Net model.

## Base Code and Modifications

The base code for the Faster R-CNN in this directory is taken and adapted from this [repository](https://github.com/RockyXu66/Faster_RCNN_for_Open_Images_Dataset_Keras), where the original objective was to detect car, mobile phone, and person objects. I've made modifications to tailor the code to the specific needs and dataset.
