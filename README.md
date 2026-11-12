# CIFAR-10 CNN Image Classification

## Project Overview

This project uses a Convolutional Neural Network (CNN) to classify images into 10 different categories from the CIFAR-10 dataset.

The model is built using TensorFlow and Keras and trained to recognize objects from small RGB images.

## Dataset Information

This project uses the CIFAR-10 dataset.

- Training Images: 50,000
- Testing Images: 10,000
- Image Dimensions: 32 × 32 pixels
- Image Channels: 3 (RGB)
- Number of Classes: 10

### Dataset Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

**Dataset Source:** https://www.cs.toronto.edu/~kriz/cifar.html

The dataset was loaded directly using TensorFlow Keras.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## CNN Model Architecture

The CNN model contains:

- Input Layer (32 × 32 × 3)
- Convolutional Layers (32, 64, 128 filters)
- Batch Normalization
- Max Pooling Layers
- Flatten Layer
- Dense Layers (128 and 64 neurons)
- Dropout Layer
- Output Layer (10 classes with Softmax)

## Model Training

- Epochs: 20
- Batch Size: 64
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Validation Split: 20%
- Hardware: Google Colab GPU (Tesla T4)

## Model Evaluation

The model was evaluated using the CIFAR-10 test dataset.

Evaluation metrics include:

- Test Accuracy
- Test Loss
- Confusion Matrix
- Classification Report

## Custom Image Prediction

The trained model can predict the class of a user-uploaded image.

It displays:

- Predicted Class
- Prediction Confidence

### Example Prediction

A sample cat image was uploaded to test the trained model.

- **Predicted Class:** Cat
- **Confidence:** 98.59%

The model successfully predicted the sample cat image.

**Note:** This confidence score belongs to one sample prediction. It is not the overall test accuracy of the model. The model predicts only among the 10 CIFAR-10 classes.

## Project Files

- `CIFAR10_CNN_Image_Classification.ipynb` — Complete project notebook.
- `CIFAR10_CNN_Image_Classification.keras` — Trained CNN model.

## Author

Kamran Ali
