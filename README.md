## **Context**

In this notebook, we will develop an image classification model that distinguishes between MRI scans showing a Pituitary Tumor and those with No Tumor.
The dataset used is publicly available on Kaggle. While the original dataset includes 3,264 images across four categories—Glioma Tumor, Meningioma Tumor, Pituitary Tumor, and No Tumor—we will focus only on two of them for this project: Pituitary Tumor and No Tumor. Our goal is to build a binary classification model for these two classes.
For training and testing, we will use a subset of 1,000 images: 830 for training (395 No Tumor, 435 Pituitary Tumor) and 170 for testing. To enhance model performance and prevent overfitting, we will apply data augmentation techniques, allowing the model to generalize better on unseen data.
We’ll begin by training a Convolutional Neural Network (CNN) from scratch and then explore performance improvement using a pre-trained architecture through the concept of Transfer Learning.
Project Objectives
    Load and explore the dataset
    Automatically label and preprocess the images
    Apply data augmentation techniques
    Build and train a CNN-based binary classification model
    Improve accuracy using Transfer Learning with a pre-trained model
