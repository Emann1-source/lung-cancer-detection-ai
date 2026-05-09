# lung-cancer-detection-ai

**Detection of Early-Stage Lung Cancer using CNN**

**Independent Research Project - Sophomore Year**

**Project Overview**
-This project uses a Convolutional Neural Network (CNN) to analyze lung CT scans and classify them as either Healthy or Early-Stage Cancer. The goal is to provide a low-cost, AI-driven screening tool that can assist in early detection.

## **The Technology**

**Model Type**: CNN (Transfer Learning)

**Platform**: Google Teachable Machine / TensorFlowBase

**Brain**: MobileNet / VGG16

**Training Data**: Kaggle

## **Methodology**

**Data Collection**: Gathered thousands of CT scan slices.

**Preprocessing**: Sorted images into two classes: Healthy and Cancer.

**Augmentation**: Used random flipping and rotation to prevent the model from memorizing specific images.

**Training**: Trained the model using a learning rate of 0.001 for 50 epochs.

## Current Results

**Training Images**:15 per class

**Test Accuracy**:70% 

**Challenges**: The model currently struggles with very small nodules or blurry images].

## How to Use
1. Use https://teachablemachine.withgoogle.com/models/j7IRbziaT/
2. Upload a .jpg or .png of a lung CT scan.
3. The model will output a probability percentage for both classes.
