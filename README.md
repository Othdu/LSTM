# CNN-LSTM Model

## Overview
This project implements a **CNN-LSTM** model designed for processing sequences of images. The architecture integrates **Convolutional Neural Networks (CNNs)** for spatial feature extraction and **Long Short-Term Memory (LSTM)** networks for temporal processing.

## Model Architecture
The model consists of the following components:

- **Convolutional Layers**: Extract spatial features from input images.
- **Max Pooling Layers**: Reduce dimensionality while preserving important information.
- **LSTM Layer**: Process temporal dependencies in image sequences.
- **Dropout Layer**: Prevent overfitting by randomly deactivating neurons.
- **Fully Connected Layers**: Perform classification based on extracted features.
