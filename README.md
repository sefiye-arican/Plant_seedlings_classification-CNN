# 🌱 Plant Seedlings Classification with CNN

A deep learning-based solution for classifying plant seedlings using Convolutional Neural Networks (CNNs). This project aims to assist in agricultural automation by accurately identifying 12 different species of seedlings from image data.

---

## 🚀 Project Overview

The primary goal of this project is to build a robust image classification model using CNN to classify seedlings into the following species:

- Black-grass
- Charlock
- Cleavers
- Common Chickweed
- Common Wheat
- Fat Hen
- Loose Silky-bent
- Maize
- Scentless Mayweed
- Shepherd’s Purse
- Small-flowered Cranesbill
- Sugar Beet

---

## 📂 Dataset

The dataset used is the **Plant Seedlings Classification** dataset, available on [Kaggle](https://www.kaggle.com/c/plant-seedlings-classification/data). It contains over 4,700 images of 12 plant species.

- Images are in RGB format with varying dimensions.
- Data is organized into subfolders named after the plant species (for training).

---

## 🧠 Model Architecture

A custom CNN was built from scratch using the Keras API in TensorFlow. The architecture includes:

- **Input Layer** with resized images (128x128)
- **3 Convolutional Blocks**: Each with Conv2D, ReLU activation, MaxPooling2D, and Dropout
- **Flatten Layer**
- **Dense Layers**: One hidden layer followed by the output layer with `softmax` activation

> ✅ Optimizer: Adam  
> 🔻 Loss Function: Categorical Crossentropy  
> 📈 Metrics: Accuracy

---

## 📊 Performance

- Achieved high accuracy on validation data.
- Trained over multiple epochs with data augmentation to prevent overfitting.
- Training and validation metrics visualized using Matplotlib.

