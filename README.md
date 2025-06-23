### Fruit Image Classification with Deep Learning Models
## Overview
This Jupyter notebook implements a fruit image classification system using various deep learning architectures. The project demonstrates a complete pipeline from dataset collection to model evaluation.

## Key Features
Dataset Collection: Uses DuckDuckGo Search API to scrape fruit images (grapes, grapefruit, apple, banana, mango, orange)

## Data Preprocessing:

Downloads and verifies image integrity

Implements data augmentation (rotation, zoom, flipping)

Splits data into training/validation sets

## Model Architectures:

CNN (Convolutional Neural Network)

MLP (Multi-Layer Perceptron)

LSTM (Long Short-Term Memory)

Autoencoder Classifier

Vision Transformer (ViT)

Evaluation: Comprehensive metrics including accuracy and confusion matrices

## Performance
The models achieved the following validation accuracies:

CNN: 70.36%

Autoencoder Classifier: 68.70%

Vision Transformer: 65.10%

MLP: 39.06%

LSTM: 29.64%

The CNN model performed best, highlighting the strength of convolutional architectures for image classification. Although the Vision Transformer showed promise, its performance was limited by the relatively small dataset size, which is a known challenge for transformer-based models that typically require large amounts of data to generalize effectively. With more data, ViT models are expected to perform significantly better.

## Technical Details
Framework: TensorFlow/Keras

Image Size: 150x150 pixels

Batch Size: 32

Epochs: 15

Data Augmentation: Rotation, zoom, horizontal flip

Validation Split: 20%

The notebook provides a solid foundation for image classification tasks and showcases how different architectures perform on the same dataset. The CNN model would be recommended for production use given its superior performance.
