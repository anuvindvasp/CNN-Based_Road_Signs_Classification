# CNN-Based-Road-Signs-Classification
![image](https://github.com/user-attachments/assets/01e256de-546b-41a8-aa56-eaddc5789242)

INTRODUCTION

Road safety is a critical aspect of transportation, and modern vehicles rely on advanced technology to minimize accidents and improve driver awareness. This project uses CNNs to recognize and classify road signs, helping ADAS interpret traffic rules accurately, contributing safer driving by reducing human errors and enhancing real-time decision-making.


Objective

To build a Convolutional Neural Network (CNN) model to classify road signs into 30 categories.
Enhance autonomous driving and improve road safety using computer vision.


Data Preprocessing

Resized images to 64x64 pixels
Normalized pixel values between 0 and 1
Labels encoded using one-hot encoding
Applied data augmentation (rotation, flip, zoom, etc.)

CNN Architecture

Input Layer: 64x64x3 Images
Convolutional + Max Pooling layers
Flatten layer
Fully connected Dense layers
Dropout for regularization
Output layer: Softmax activation


