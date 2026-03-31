# Face-Mask-Detection-CNN
A convolutional neural network (CNN) model implemented in TensorFlow/Keras for real-time face mask detection from images. This project trains a CNN on a dataset of masked and unmasked faces to classify whether a person is wearing a mask.

## Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to detect whether a person in an image is wearing a face mask or not. The model is trained on a custom dataset of masked and unmasked faces to achieve high accuracy in classification.

## Dataset
The model was trained on the [Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset) from Kaggle, which includes images categorized into 'with_mask' and 'without_mask'.

## Model Architecture
The CNN architecture consists of:
*   Convolutional layers with ReLU activation.
*   Max Pooling layers for downsampling.
*   Flatten layer to convert 2D feature maps to 1D feature vectors.
*   Dense (fully connected) layers with ReLU activation.
*   A final Dense layer with Sigmoid activation for binary classification.

## Technologies Used
*   Python 3.x
*   TensorFlow
*   Keras
*   Numpy
*   Matplotlib
*   OpenCV (cv2)
*   Pillow (PIL)
*   scikit-learn


# Results
The model achieved a test accuracy of approximately (92.19%) on the unseen test data.
