# CNN-Based Road Signs Classification
![image](https://github.com/user-attachments/assets/01e256de-546b-41a8-aa56-eaddc5789242)
<p align="center">
  <img src="https://github.com/user-attachments/assets/ac5eb98e-42f0-46f0-97ea-7a3264d2c14a" width="400"/>
  &nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/ddaeaf85-0b75-4c5a-9b6c-57baef7f80a0" width="400"/>
</p>

## INTRODUCTION

Road safety is a critical aspect of transportation, and modern vehicles rely on advanced technology to minimize accidents and improve driver awareness. This project uses CNNs to recognize and classify road signs, helping ADAS interpret traffic rules accurately, contributing safer driving by reducing human errors and enhancing real-time decision-making.


## Objective

To build a Convolutional Neural Network (CNN) model to classify road signs into 30 categories.
Enhance autonomous driving and improve road safety using computer vision.

## Dataset

The dataset comprises a vast collection of labeled images of traffic signs, organized into various categories, each corresponding to a distinct type of road sign like Stop, Speed Limit, Yield, and others.

## Data Preprocessing

Resized images to 64x64 pixels
Normalized pixel values between 0 and 1
Labels encoded using one-hot encoding
Applied data augmentation (rotation, flip, zoom, etc.)

## CNN Architecture

Input Layer: 64x64x3 Images

Convolutional Layers (Conv2D)

Max Pooling layers (MaxPooling2D)

Flatten layer

Fully connected Dense layers

Dropout layers for regularization

Output layer : Softmax activation

Optimizer: Adam

Hyperparameter Optimization : Keras Tuner


### Model Accuracy:

Training Accuracy   : ~0.9981

Validation Accuracy : ~0.9009

Test Accuracy       : ~0.8750

These results reflect a robust model capable of delivering accurate predictions on previously unseen data, demonstrating strong generalization performance.

## Streamlit Web App

An intuitive and user-friendly web interface was developed using Streamlit to:

* Upload and test images
* Display predicted road sign labels
* Present confidence scores and key performance metrics

## Conclusion

This Road Sign Classifier, powered by CNN, showcases how deep learning can be effectively utilized in intelligent transportation. With its high accuracy, the model holds strong potential for deployment in real-time applications such as autonomous vehicles and traffic safety systems.

