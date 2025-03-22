# 🧠 CIFAR-10 Image Classification using CNN

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ncqxm/cifar10-cnn/blob/main/CIFAR_10_cnn.ipynb)

This project implements a custom Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images in the CIFAR-10 dataset.

---

## Features

- Custom CNN with BatchNormalization and Dropout
- Trained on 10 classes of CIFAR-10 dataset
- Achieved up to 87% test accuracy
- Visualizations:
  - Training Accuracy & Loss
  - Confusion Matrix
  - Classification Report

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-informational)

---
## Results

### Confusion Matrix  
![Confusion Matrix](images/confusion_matrix.png)

### Training Curves  
![Training Metrics](images/training_metrics.png)

---

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/cifar10-cnn.git
   cd cifar10-cnn
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook:
   Open cifar10_cnn.ipynb using Jupyter or Colab
