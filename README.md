# 🧠 CNN for Image Classification (CIFAR-10)

This project implements a **Convolutional Neural Network (CNN)** using PyTorch to perform image classification on the **CIFAR-10 dataset**. The model is designed to learn visual features such as edges, textures, and patterns to accurately classify images into 10 categories.

---

## 📌 Project Overview

* Built a custom CNN architecture using **PyTorch**
* Trained and evaluated the model on the **CIFAR-10 dataset**
* Applied data transformations and normalization
* Implemented training and validation loops
* Optimized using **Adam optimizer** and **CrossEntropyLoss**

---

## 📂 Dataset

The dataset used is **CIFAR-10**, which contains:

* 60,000 color images (32x32 pixels)
* 10 classes:

  * Airplane ✈️
  * Automobile 🚗
  * Bird 🐦
  * Cat 🐱
  * Deer 🦌
  * Dog 🐶
  * Frog 🐸
  * Horse 🐴
  * Ship 🚢
  * Truck 🚚

Dataset is automatically downloaded using `torchvision.datasets`.

---

## 🏗️ Model Architecture

The CNN consists of:

### 🔹 Convolutional Layers

* 3 Convolutional blocks:

  * Conv2D → ReLU → MaxPooling
* Feature extraction from images

### 🔹 Fully Connected Layers

* Flattening layer
* Dense layers:

  * 2048 → 256 → 10

---

## ⚙️ Tech Stack

* Python 🐍
* PyTorch 🔥
* Torchvision
* Jupyter Notebook

---

## 🚀 Training Details

* Loss Function: `CrossEntropyLoss`
* Optimizer: `Adam`
* Learning Rate: `0.001`
* Input Size: `3 x 32 x 32`

---

## 📊 Results

* The model successfully learns to classify images across all 10 classes
* Achieves good performance with increasing epochs
* Can be further improved using:

  * Dropout
  * Batch Normalization
  * Data Augmentation

---

## 💡 Key Learnings

* Understanding CNN architecture and feature extraction
* Working with image datasets in PyTorch
* Model training, evaluation, and debugging
* Importance of correct tensor shapes and transformations

---

## 🔧 Future Improvements

* Add Batch Normalization for better convergence
* Use Dropout to prevent overfitting
* Experiment with deeper architectures
* Try transfer learning (ResNet, VGG)

---

## 🤝 Connect With Me

**Riya Jain**
AI & ML Enthusiast | B.Tech CSE at MIT ADT University

* GitHub: https://github.com/TheRedCoder777

---

⭐ If you like this project, feel free to star the repo!
