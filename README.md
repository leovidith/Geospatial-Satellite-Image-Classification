# Geospatial Satellite Image Classification

## Overview
This project focuses on classifying geospatial satellite images using deep learning models. We compare multiple architectures and achieve a **98% accuracy** with ResNet50V2.

## Features
- Data preprocessing and augmentation
- Implementation of VGG, Inception ResNet, Xception, and ResNet50V2
- Model evaluation using classification reports and confusion matrices
- Prediction on test data with probability scores

## Dataset
- Satellite image dataset used for classification
- Preprocessed and split into training and validation sets

## Model Performance
| Model           | Validation Accuracy | Validation Loss |
|----------------|--------------------|----------------|
| VGG           | 91%                | 0.24            |
| Inception ResNet | 57%                | 1.1            |
| Xception      | 83%                | 0.52            |
| ResNet50V2    | 98%                | 0.08            |

## Results
- Classification performance is analyzed using confusion matrices.
- Model accuracy and loss are plotted for comparison.
