
# Bottle Detection and Segmentation

This project focuses on employing machine learning models to identify (detection) and segment bottles within images. The process is divided into two main phases: Detection using the Faster R-CNN model, followed by Segmentation using the U-Net model. Additionally, there's a transition notebook that bridges the detection results to segmentation.

## Project Structure

- 📂 **Faster_R_CNN_for_detection**
  - 📜 ... (Additional contents of Faster R-CNN directory)
- 📂 **U_Net_for_segmentation**
  - 📜 ... (Additional contents of U-Net directory)
- 📜 **detection_to_segmentation.ipynb**

**Note**: For clarity and repository size considerations, subdirectories that originally contained images, masks, CSV files, and annotations have been pushed in their empty state. This ensures that the structure of the project is evident without overloading the repository with large data files.

## Faster R-CNN for Detection

The `Faster_R_CNN_for_detection` directory is dedicated to the detection phase. Within this phase, images are processed to identify and locate bottles. The Faster R-CNN model is utilized to achieve this. 

## U-Net for Segmentation

Post detection, the next step is to segment the identified bottles. This is where the `U_Net_for_segmentation` directory comes into play. Inside this directory, one can find the scripts required to prepare the data, train and fine-tune the U-Net model specifically for bottle segmentation.

## Transitioning from Detection to Segmentation

The detection_to_segmentation.ipynb notebook serves as a bridge between the detection and segmentation phases. Once the trained models for both detection and segmentation are loaded, the notebook processes the Faster R-CNN outputs, prepares the data, and transitions to the segmentation phase. It illustrates how the detected outputs can feed into the segmentation model.

