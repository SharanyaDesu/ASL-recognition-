# American Sign Language Alphabet Recognition using Deep Learning
# Overview
This project focuses on recognizing American Sign Language (ASL) alphabets using deep learning techniques. The goal is to provide a real-time system that translates ASL signs into text or spoken language, enhancing communication accessibility for the deaf and hard of hearing community.

![image](https://github.com/user-attachments/assets/138ade30-b9da-4269-97ac-5e16e86253c5)

# Features
Real-time ASL alphabet recognition using a Convolutional Neural Network (CNN) model.
Preprocessing techniques like one-hot encoding and normalization of RGB values.
Training and evaluation of the model on a large dataset of 87,000 images.
Future improvements include data augmentation, attention mechanisms, and multimodal learning.


# Table of Contents
Dataset,
Preprocessing techniques,
Model Architecture,
Implementation,
Results,
Future Work

# Dataset
The dataset consists of 87,000 images of ASL alphabet gestures. It is divided into:

Training Set: 60,900 images
Validation Set: 17,400 images
Testing Set: 8,700 images
The images are resized to 32x32 pixels and normalized to improve model performance.


# Preprocessing techniques
One-Hot Encoding: One-hot encoding converts categorical labels into a binary matrix, where each label is represented as a unique vector with a single '1' and the rest '0s,' making it suitable for classification by the model.

![image](https://github.com/user-attachments/assets/6efb8223-3545-422e-b2d1-a86a24e8d2b9)

Normalize RGB Values: Normalizing RGB values scales the pixel intensity of images to a range of 0 to 1, reducing the influence of lighting variations and improving the model's ability to learn patterns effectively.

![image](https://github.com/user-attachments/assets/6f27bd92-1e9f-4932-849f-4f2f8531fdeb)

# Model Archietecture
The model is a Convolutional Neural Network (CNN) with the following key components:

Multiple convolutional layers for feature extraction
Batch normalization layers to stabilize training
Dropout layers for regularization
Dense layers for classification
For detailed architecture, refer to the ASL_Architecture file


# Implementation
The implementation of this project involves training a Convolutional Neural Network (CNN) to recognize American Sign Language (ASL) alphabet gestures. The process begins with data preprocessing, where images are normalized, and labels are one-hot encoded. The CNN model is then constructed with multiple layers for feature extraction and classification. Training and evaluation are conducted on the ASL dataset, achieving high accuracy in recognizing gestures. The code for this implementation is detailed in the asl-classification-using-cnn.ipynb file.

![image](https://github.com/user-attachments/assets/db2cbcc1-2bc1-4360-97a9-57e590309b17)



# Results
Training Accuracy: 99.46%
Validation Accuracy: 91.40%
Testing Accuracy: 91.09%
These results are indicative of the model's strong ability to generalize to unseen data.

![image](https://github.com/user-attachments/assets/dc8e1b4d-0420-458a-a92e-9415c7e518f8)

# Future Work
Planned improvements include:

Data Augmentation: Increase diversity in training samples.
Attention Mechanisms: Implement attention layers for better focus on relevant regions.
Multimodal Learning: Incorporate depth information and temporal data for dynamic gesture recognition.


