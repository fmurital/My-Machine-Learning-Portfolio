# Artwork Genre Classification Using Transfer Learning

## Overview

This project applies deep learning and transfer learning techniques to classify artwork into different genres. The model leverages a pretrained VGG16 architecture and adapts it for image classification using a limited dataset.

## Objective

Develop an image classification model capable of identifying artwork genres from visual features.

## Methods

### Data Preparation
- Collected and organized artwork images
- Performed image preprocessing and normalization
- Split data into training and testing sets

### Transfer Learning
- Utilized a pretrained VGG16 convolutional neural network
- Replaced final classification layers for genre prediction
- Fine-tuned the model for the artwork dataset

### Model Optimization
- Applied Batch Normalization
- Implemented Dropout regularization
- Reduced overfitting while improving generalization

### Evaluation
- Measured classification accuracy
- Assessed model performance on previously unseen images

## Technologies Used

- Python
- TensorFlow
- Keras
- VGG16
- Deep Learning
- Computer Vision

## Skills Demonstrated

- Transfer Learning
- Computer Vision
- Image Classification
- Convolutional Neural Networks
- Deep Learning

## Key Achievement

Achieved approximately 47% classification accuracy using a limited dataset consisting of roughly 45 samples per class.

## Challenges

The dataset was relatively small, making generalization difficult. Transfer learning enabled effective feature extraction and improved performance despite limited training data.

## Files

- [`Fmurital_Transfer_Learning.ipynb`](https://github.com/fmurital/My-Machine-Learning-Portfolio/blob/main/04-Art-Classification/Fmurital_Transfer_Learning.ipynb) – Complete project notebook

## Author

Faruk Muritala
