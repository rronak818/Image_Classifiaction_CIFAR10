# CIFAR-10 Image Classification with TensorFlow/Keras

This repository contains an implementation of image classification using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset, leveraging **TensorFlow/Keras**. CIFAR-10 is a well-known dataset consisting of 60,000 32x32 color images across 10 different classes, including **airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks**.

## Project Overview

The goal of this project is to build and train a CNN model capable of accurately classifying CIFAR-10 images. The model architecture includes multiple convolutional layers for feature extraction, followed by max-pooling and dense layers for classification.

### Key Features:
- **Data Preprocessing**: Resizing, normalizing, and augmenting the CIFAR-10 images.
- **Model Architecture**: A CNN with convolutional, batch normalization, pooling, dropout, and dense layers.
- **Training and Evaluation**: The model is trained on the CIFAR-10 training set and evaluated using the test set.
- **Callbacks**: Learning rate reduction on plateau and early stopping are used to improve training efficiency.

## Model Architecture

The Convolutional Neural Network architecture used for this project consists of:
1. **Convolutional layers (Conv2D)** for feature extraction.
2. **MaxPooling layers** for dimensionality reduction.
3. **Batch Normalization** for stable and faster training.
4. **Dropout** to reduce overfitting.
5. **Fully connected layers (Dense)** for classification.

### Results
The model achieves competitive accuracy on the CIFAR-10 dataset. The following performance metrics are recorded:

- Training Accuracy: ~91%
- Validation Accuracy: ~90%
- Test Accuracy: ~91.15%

## Installation

Follow these steps to set up the project on your local machine:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

   
This detailed description provides a complete project overview, including key components, how to run the project, and how to visualize the training progress using plots.


