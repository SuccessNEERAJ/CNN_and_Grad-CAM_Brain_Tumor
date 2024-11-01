# CNN with Grad-CAM for Brain Tumor Detection

This repository contains an implementation of a Convolutional Neural Network (CNN) combined with Gradient-weighted Class Activation Mapping (Grad-CAM) for detecting brain tumors from MRI images. Grad-CAM is used to visualize the regions of MRI images that the CNN focuses on to make predictions, aiding in interpretability for medical applications.

## Overview

Detecting brain tumors from MRI scans is a critical task that requires high accuracy and interpretability. This project leverages a CNN model to classify brain tumor types and employs Grad-CAM to visualize and interpret the model's focus areas, helping clinicians understand the decision-making process and identify key features in the MRI scans.

## Features

- **Convolutional Neural Network (CNN)**: Implements a CNN model optimized for classifying MRI images based on the presence and type of brain tumor.
- **Grad-CAM Visualization**: Provides class activation mappings that highlight the regions in MRI images that contribute most to the CNN's classification decisions, enhancing model transparency.
- **Easy Customization**: Allows easy customization of model parameters such as learning rate, number of epochs, and CNN architecture layers.

## Dataset

The model is trained on a structured brain tumor MRI dataset with four classes of images across training and testing sets:


Each folder within `Training` and `Testing` contains MRI images labeled as one of the four categories: `notumor`, `glioma`, `meningioma`, and `pituitary`.

## Results

The model accurately classifies MRI images across the four categories. Grad-CAM visualizations illustrate the critical regions within MRI images that the CNN model focuses on, allowing for greater interpretability of predictions.

## License

Neeraj Jaiswal and Karanbir Singh