# Retinal Disease Detection

This repository contains code for a deep learning project aimed at detecting retinal diseases from retinal images. The project uses convolutional neural networks (CNNs) to classify retinal images into different disease categories.

## Overview

Retinal diseases, such as age-related macular degeneration (ARMD), diabetic retinopathy (DR), and others, are leading causes of blindness worldwide. Early detection and diagnosis of these diseases are crucial for timely intervention and treatment.

In this project, we develop a deep learning model that can automatically classify retinal images into different disease categories based on image features. The model is trained on a dataset of retinal images labeled with disease categories.

## Dataset

The dataset used in this project consists of retinal images collected from various sources. Each image is labeled with one or more disease categories, including ARMD, DR, macular hole (MH), and others. The dataset is divided into training, validation, and test sets for model development and evaluation.

## Model Architecture

The deep learning model is built using TensorFlow and Keras. It consists of multiple convolutional layers followed by max-pooling layers for feature extraction. The extracted features are then passed through fully connected layers for classification. The model is trained using the Adam optimizer with binary cross-entropy loss.

## Usage

1. Clone the repository to your local machine:
https://github.com/nushan2000/Rational-Disease-Classification.git

2. Install the required dependencies
3. Download the dataset and update the file paths in the code accordingly.
4. Train the model using the provided scripts:
5. Evaluate the model on the test set:

## Results

The trained model achieves an accuracy of 84.22% on the test set, demonstrating its effectiveness in detecting retinal diseases.
