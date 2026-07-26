# Advanced Optical Character Recognition (OCR) Engine

## Project Overview

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The model is trained to classify images of digits from 0 to 9 with high accuracy.

## Objectives

- Load and preprocess the MNIST dataset.
- Build a CNN model using TensorFlow/Keras.
- Train the model on handwritten digit images.
- Evaluate the model using the test dataset.
- Predict handwritten digits from unseen images.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

## Dataset

- MNIST Handwritten Digits Dataset
- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels

## CNN Architecture

- Conv2D (32 Filters, 3×3, ReLU)
- MaxPooling2D (2×2)
- Flatten
- Dense (128, ReLU)
- Dense (10, Softmax)

## Model Performance

After training for 5 epochs, the model achieved high accuracy on the test dataset.


## Author

**Samar Babar**
