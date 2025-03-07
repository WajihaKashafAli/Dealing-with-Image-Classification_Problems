# 🧠 Deep Learning for Computer Vision: Cat vs. Dog Classification
## 📌 Project Overview
This project implements a deep learning model for binary image classification, distinguishing between cats and dogs. The model is trained on a smaller, curated dataset to test the effectiveness of convolutional neural networks (CNNs) even with limited data.

## 📂 Dataset
- <a href="https://www.kaggle.com/competitions/dogs-vs-cats/data">Dataset</a>

## 🎯 Objectives
Develop a robust cat vs. dog classifier with a smaller dataset.
Prevent overfitting with techniques like data augmentation and regularization.
Achieve high accuracy with careful model tuning and evaluation.

## 📊 Dataset Used
A reduced version of the cat vs. dog dataset:
Training: 1000 cat images, 1000 dog images
Validation: 500 cat images, 500 dog images
Testing: 500 cat images, 500 dog images

![screenshort](https://github.com/user-attachments/assets/4b50b1f3-25df-4bb9-b4d5-43d8e150dffd)
![screenshort1](https://github.com/user-attachments/assets/92db774d-2f6b-48ef-b0b5-0bc9610040f8)

## ⚙️ Model Architecture
Custom CNN with multiple convolutional layers.
Transfer Learning with models like VGG16 for feature extraction.
ReLU activations, MaxPooling layers, and Dropout for regularization.

## 🚀 Training Process
Preprocessing: Image resizing, normalization, and augmentation (flipping, rotation, etc.).
Training: Model trained with techniques like batch normalization and early stopping.
Validation: Performance monitored to avoid overfitting and adjust hyperparameters.

## 📈 Results:
Training Accuracy: ~100%
Validation Accuracy: ~93%
Test Accuracy: ~93%

## 🛠️ Technologies Used:
Python, TensorFlow, Keras, NumPy, Matplotlib.
Jupyter Notebooks for experimentation and visualization.

## 🏁 Conclusion:
This project highlights the power of deep learning for small-scale image classification tasks. By using a well-structured CNN and employing best practices like augmentation and regularization, it’s possible to build a highly accurate model even with limited data.
