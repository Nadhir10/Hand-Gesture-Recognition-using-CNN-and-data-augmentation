# Hand Gesture Recognition using CNN and data augmentation

## Project Overview

This GitHub repository contains the implementation of a hand gesture recognition system using deep learning techniques. The project focuses on recognizing hand gestures from images, enabling applications such as sign language interpretation, gesture-based control systems, and more. The key components of this project include data augmentation and a convolutional neural network (CNN) for accurate and robust gesture recognition.
The project was developed during my Master's studies in Artificial Intelligence.

## Problem Statement

Recognizing hand gestures accurately is a challenging task due to variations in lighting conditions, backgrounds, and hand orientations. This project addresses these challenges by leveraging data augmentation techniques and a well-designed CNN architecture.

## Dataset

The project utilizes a diverse and comprehensive dataset of hand gesture images. The dataset includes various gestures performed by different individuals under different conditions. The dataset was preprocessed to ensure consistency in image size and quality.

## Solution

### Data Augmentation

Data augmentation is a crucial step in enhancing the diversity of the dataset. Augmentation techniques such as rotation and flipping were applied to generate additional training samples. This process helps the model generalize better to unseen data and improves its performance.

### Convolutional Neural Network (CNN)

A CNN architecture was designed and trained on the augmented dataset. CNNs are well-suited for image recognition tasks as they can automatically learn hierarchical features from the input images. The architecture consists of multiple convolutional layers followed by max-pooling layers to extract essential features from the images. Dropout layers were added to prevent overfitting, and fully connected layers were used for classification.

The model was trained using an appropriate loss function and optimizer to minimize the classification error. 

## Results  

The trained model achieved a high accuracy rate on the test dataset, demonstrating its ability to recognize hand gestures effectively. 

## real Time test

Despite not being trained for a real time execution, yet the model performs well on real-time feed. The last part of the notebook allows testing the model with a Webcam.
