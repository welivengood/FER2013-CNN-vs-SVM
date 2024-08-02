# FER2013-CNN-vs-SVM

This project was completed in collaboration with Garrett Rider and Marissa Lane.

## Project Overview

This report explores emotion recognition from facial expressions using Support Vector Machine (SVM) and Convolutional Neural Network (CNN) models. Using the FER2013 dataset, images are preprocessed and divided into training and testing sets. An SVM classifier is trained on flattened image data to predict emotion labels, while a CNN model, built with TensorFlow's Keras API, extracts features directly from images.
Model Details

  * SVM Model: Trained on flattened image data to predict emotion labels.
  * CNN Model: Comprises convolutional layers with ReLU activation, followed by max-pooling and dense layers.

## Findings

  * Performance: The CNN model outperforms the SVM, achieving higher accuracy despite challenges such as data imbalance and underfitting.
  * Comparison: While SVM demonstrates efficiency in small datasets, CNN excels in complex classification tasks with larger datasets, showcasing its capability in facial recognition and emotion detection.
  * Challenges: Incomplete facial visibility and non-face images within the dataset hindered our analysis.

## Dataset

The database used for this project can be found [here](https://www.kaggle.com/datasets/msambare/fer2013).
