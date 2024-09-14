Flower Classification using Convolutional Neural Networks (CNNs)
This Python script uses TensorFlow and Keras to build a Convolutional Neural Network (CNN) for classifying flowers into five different species: roses, daisies, dandelions, sunflowers, and tulips.

Dataset
The Oxford Flowers Dataset is used, consisting of 1020 images. Images are automatically downloaded via TensorFlow's get_file() function and split into training and testing sets.

Code Structure
Data Preparation: The dataset is loaded, images resized, and the data split into training and testing sets.
Model Definition: A CNN is defined with multiple convolutional and pooling layers, followed by fully connected layers.
Model Compilation: The model is compiled using the Adam optimizer and sparse_categorical_crossentropy loss.
Model Training: The model is trained for 30 epochs on the training dataset.
Data Augmentation: A data augmentation layer is added to enhance the dataset via transformations.
Model Training with Data Augmentation: The model is retrained for 30 epochs with augmented data.
Requirements
TensorFlow 2.x
Keras 2.x
NumPy
OpenCV
scikit-learn
PIL
