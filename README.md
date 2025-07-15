# Lung Segmentation Using U-Net

This project implements lung segmentation from chest X-ray images using a U-Net convolutional neural network. It is designed to isolate lung regions for preprocessing in medical image analysis tasks such as disease detection (e.g., pneumonia, COVID-19).

##  Overview

- Trains a U-Net model on chest X-ray datasets
- Performs pixel-wise segmentation to extract lung masks
- Evaluates segmentation performance using metrics like IoU and Dice Score

##  Libraries and Tools Used

- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- OpenCV
- Google collab

##  Features

- U-Net architecture for biomedical image segmentation
- Preprocessing pipeline with resizing and normalization
- Visual comparison of the original image, ground truth, and prediction

##  File Structure

- `lung segmentation using U-net.ipynb`: Complete pipeline including model training, evaluation, and visualization

##  Evaluation Metrics

- Dice Similarity Coefficient (DSC)
- Intersection over Union (IoU)
