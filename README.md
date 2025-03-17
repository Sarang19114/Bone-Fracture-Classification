# 🦴 Bone Classification Project

## 📌 Overview
This project is a deep learning model trained on a Kaggle dataset to classify whether a bone X-ray image indicates a fracture or not. The model utilizes Convolutional Neural Networks (CNNs) for binary classification of medical images.

## 📂 Dataset
- The dataset is sourced from **Kaggle** : https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data and contains labeled X-ray images indicating fractures or no fractures.
- Preprocessing steps include:
  - Image normalization
  - Data augmentation
  - Resizing images to fit the model's input requirements

## 🏗️ Model Architecture
- The model is built using **TensorFlow**.
- It consists of multiple **convolutional layers, max pooling layers, and dense layers**.
- Uses **ReLU activation** in hidden layers and **Sigmoid activation** for binary classification.
- Optimized with **Adam optimizer** and **binary cross-entropy loss function**.

## 🚀 Training
- The dataset is split into **training and validation sets**.
- Trained using **batch normalization and dropout** to prevent overfitting.
- Uses **early stopping** to optimize performance.

## 🎯 Future Enhancements
- **Grad-CAM Visualization**: Implementing Grad-CAM to highlight areas influencing the model’s decision.
- **Hyperparameter Tuning**: Experimenting with different architectures and optimizers.
- **Deployment**: Converting the model into a web application for real-world usage.

### Present the same at ISDRIS'25 and AICraft2.1

Feel free to contribute or report issues!

