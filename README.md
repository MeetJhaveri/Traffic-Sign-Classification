## Traffic Sign Classification

This repository contains the implementation of a deep learning model for Traffic Sign Classification using Convolutional Neural Networks (CNNs). The goal of this project is to accurately classify traffic signs from the German Traffic Sign Dataset (GTSRB) to aid in autonomous driving systems.

Traffic sign recognition is a critical component for self-driving cars and advanced driver-assistance systems (ADAS). In this project, we built a CNN-based model to classify traffic signs with high accuracy. The dataset used is the German Traffic Sign Recognition Benchmark (GTSRB), which contains more than 40 different traffic sign classes.

## Features
- **CNN-based Architecture:** A deep learning model that efficiently classifies traffic signs into multiple categories.
- **Data Augmentation:** Techniques like rotation, zoom, and histogram equalization are applied to enhance the model’s generalization capability.
- **Multi-Class Classification:** Supports classification for 43 distinct classes of traffic signs.

## Dataset
The dataset used is the German Traffic Sign Recognition Benchmark (GTSRB), which consists of 43 classes of traffic signs.

- **Number of Images:** 51,839
- **Image Resolution:** 32x32 pixels
- **Classes:** 43 distinct types of traffic signs

## Model Architecture
The Convolutional Neural Network (CNN) architecture consists of:

- **Input Layer:** Image size of 32x32 pixels with RGB channels.
- **Convolutional Layers:** Multiple layers for feature extraction using filters.
- **Max-Pooling Layers:** To reduce the dimensionality and computational complexity.
- **Dense Layers:** Fully connected layers for classification.
- **Softmax Layer:** For multi-class classification (43 classes).

## Results

- **Training Accuracy:** ~99%
- **Test Accuracy:** 97% on the test set.
