# Deep-learning-animal-classifier

## Project Overview

This project focuses on building an image classification model to distinguish between cats and dogs using a deep learning approach. The model is developed using a pre-trained VGG19 network, which is a popular convolutional neural network (CNN) architecture.

The goal is to apply transfer learning to improve classification performance while reducing training time and computational cost.

## Objective
To classify images into two categories: Cat and Dog
To utilize a pre-trained CNN model (VGG19) for feature extraction
To understand the concept of transfer learning in deep learning

## Methodology
1. Dataset

The dataset consists of labeled images of:

Cats 
Dogs 

The data is divided into:

Training set
Validation/Test set

## Model Used: VGG19
VGG19 is a deep convolutional neural network with 19 layers
It is pre-trained on large datasets like ImageNet
Used here as a feature extractor

## Transfer Learning

Instead of training from scratch:

Pre-trained weights of VGG19 are used
Final layers are modified for binary classification (Cat vs Dog)
Only selected layers are trained (fine-tuning)

## Training Process
The model learns patterns from training images
Loss function and optimizer are used to improve accuracy
Performance is evaluated using validation data

## Applications
Image recognition systems
Animal classification
AI-based surveillance systems
Educational deep learning projects
