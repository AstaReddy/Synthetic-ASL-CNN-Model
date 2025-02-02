# ASL Recognition with CNN

Overview

This project is dedicated to the development of a Convolutional Neural Network (CNN) using TensorFlow and Keras for the recognition of American Sign Language (ASL) gestures. The model is trained and evaluated on a synthetic ASL alphabet dataset, aiming to accurately classify ASL signs into their corresponding alphabets.

Features

Data Preprocessing: Implementation of image preprocessing techniques suitable for ASL gesture images.
CNN Model: A deep learning model using TensorFlow and Keras to learn and predict ASL signs.
Model Evaluation: Techniques including confusion matrices and accuracy assessment to evaluate model performance.
Visualization: Utility scripts for visualizing true vs. predicted labels and model performance metrics.

Dataset

The dataset used comprises synthetic images representing the ASL alphabet. Each image is a grayscale representation of a hand gesture corresponding to a letter in the alphabet.

Model Architecture

The CNN model includes multiple convolutional layers, max pooling, and dense layers, along with dropout and batch normalization for regularization. The final layer uses a softmax activation function for multi-class classification of the 26 ASL alphabet signs.
