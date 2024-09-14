Flower Classification using Convolutional Neural Networks (CNNs)

Overview

This repository contains a Python script that uses TensorFlow and Keras to build a convolutional neural network (CNN) for classifying flowers into five different species: roses, daisies, dandelions, sunflowers, and tulips.

Dataset

The dataset used for this project is the Oxford Flowers Dataset, which consists of 1020 images of flowers from the five species mentioned above. The dataset is downloaded using TensorFlow's get_file function.

Code Structure

The code is divided into the following sections:

1. Data Preparation: Loads the dataset, resizes images to 180x180 pixels, and splits the data into training and testing sets.
2. Model Definition: Defines a CNN model with three convolutional layers, max pooling layers, and two dense layers.
3. Model Compilation: Compiles the model with the Adam optimizer and sparse categorical crossentropy loss function.
4. Model Training: Trains the model on the training data for 30 epochs.
5. Data Augmentation: Defines a data augmentation layer to randomly flip, rotate, and zoom images.
6. Model Training with Data Augmentation: Trains the model with data augmentation on the training data for 30 epochs.

Requirements

- TensorFlow 2.x
- Keras 2.x
- NumPy
- OpenCV
- scikit-learn
- PIL

Usage

1. Clone the repository.
2. Run the script using Python (e.g., python (link unavailable)).
3. The model will be trained and evaluated on the test data.
