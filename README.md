Hand Gesture Recognition Model:

This repository contains a deep learning model for recognizing hand gestures. The model is trained on a custom dataset of images with various hand gestures and is designed to classify images into one of ten gesture classes.

Project Overview:

The goal of this project is to create a deep learning model that can accurately identify and classify different hand gestures from image data. This can be used in various applications such as human-computer interaction, gesture-based control systems, and more.

Dataset: https://www.kaggle.com/datasets/roobansappani/hand-gesture-recognition/data
The dataset consists of images of hands showing various gestures.

Model Architecture
The model is a Convolutional Neural Network (CNN) built using TensorFlow and Keras. The architecture consists of:

Input Layer: 128x128 RGB images
Convolutional Layers: Several Conv2D layers with ReLU activation and MaxPooling
Dropout Layers: For regularization to prevent overfitting
Flatten Layer: Converts the 2D matrix data to a vector
Dense Layers: Fully connected layers with ReLU activation
Output Layer: A softmax layer with 10 units, one for each class
Training
The model was trained using the following configuration:

Optimizer: Adam
Loss Function: Categorical Crossentropy
Metrics: Accuracy
Data Augmentation: Applied using ImageDataGenerator to increase the dataset's variability and improve generalization
