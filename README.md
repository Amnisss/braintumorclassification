# Image Classification Model for Brain Tumor Diagnosis

This repository contains an image classification model developed using Convolutional Neural Networks (CNN) based on the ResNet50 architecture. The model is designed for accurate diagnosis of brain tumors from MRI scans. I have also included metrics (training & validation loss and confusion matrix) and one of my trained models as a .pb

## Background

In 2023, 18,990 Americans died from brain tumors. Traditional diagnostic approaches relying on visual interpretation by radiologists often lead to high false negative rates, resulting in missed or delayed diagnoses. An AI model offers the potential to improve diagnostic accuracy and efficiency through advanced image processing algorithms and machine learning techniques.

## Features

- Implemented a CNN based on ResNet50 using TensorFlow Keras for brain tumor diagnosis.
- Evaluated validation and training loss dynamics to optimize epoch iterations and learning rate.
- Utilized data augmentation techniques for improved model generalization.

## Dataset Information

The dataset used for training and testing the model was obtained from [Kaggle - Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection). It contains 1669 MRI scans of healthy brains and 2010 MRI scans showing brain tumors. The dataset was preprocessed and augmented using techniques such as data normalization, resizing, and data augmentation (e.g., rotation, flipping, zooming) to enhance the quality and diversity of the training data. 

## Results and Performance

The trained image classification model achieved the following performance metrics:

- **Accuracy:** Up to 99%
- **Precision:** 98.11%
