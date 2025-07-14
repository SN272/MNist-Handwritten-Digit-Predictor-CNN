# ✍️ MNIST Handwritten Digit Recognition using CNN

This project implements a **Convolutional Neural Network (CNN)** from scratch to classify handwritten digits (0–9) using the **MNIST dataset**. Built as part of the *"Python for Deep Learning: Build Neural Networks in Python"* course, the model is developed using **TensorFlow**, **Keras**, and **Python**, and executed in **Google Colab**.

---

## 📌 Objective

To train a deep learning model capable of accurately identifying handwritten digits by learning from thousands of labeled image samples using convolutional layers, pooling, and dense networks.

---

## 🗃️ Dataset

- **MNIST** dataset (preloaded in TensorFlow/Keras)
- Contains **70,000 grayscale images** (28x28 pixels) of digits from 0 to 9:
  - 60,000 for training
  - 10,000 for testing

---

## 🛠️ Technologies Used

- **Python**  
- **TensorFlow / Keras**  
- **NumPy**  
- **Matplotlib**  
- **Google Colab / Jupyter Notebook**

---

## 🧠 Model Architecture

- **Input Layer:** 28x28 grayscale image  
- **Convolutional Layer 1:** 32 filters (3x3), ReLU activation  
- **Max Pooling Layer 1:** 2x2 pool size  
- **Convolutional Layer 2:** 64 filters (3x3), ReLU activation  
- **Max Pooling Layer 2:** 2x2 pool size  
- **Flatten Layer**  
- **Dense Layer:** 64 units, ReLU activation  
- **Output Layer:** 10 units (Softmax for multiclass classification)

---

## 📊 Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- Loss Curve and Accuracy Curve over epochs

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SN272/MNist-Handwritten-Digit-Predictor-CNN.git
