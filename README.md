# 🔢 MNIST Digits Classification with Deep Learning

A deep learning project that classifies handwritten digits (0–9) using the MNIST dataset and a neural network built with TensorFlow/Keras.

---

## 📌 Project Overview

This project demonstrates how to build and train a simple neural network to recognize handwritten digits using the classic **MNIST dataset**, which contains 70,000 labeled images of handwritten digits (28x28 pixels, grayscale).

---

## 🧠 Model Architecture

The neural network used in this project follows a simple architecture:

- Input layer: 784 neurons (28x28 image flattened)
- Hidden layer(s): Dense layers with ReLU activation
- Output layer: 10 neurons (one for each digit), with softmax activation

> ✅ Optimizer: Adam  
> 📉 Loss Function: Categorical Crossentropy  
> 🧪 Evaluation Metric: Accuracy

---

## 📊 Results

- **Training Accuracy**: ~95%
- **Test Accuracy**: ~95%
- **Model Size**: Small and fast to train

Sample results and accuracy graphs included in the notebook.

---

## 📁 Project Structure
```bash
.
├── main.ipynb
└── README.md

1 directory, 2 files
```
## Future work
- Add confusion matrix
- Utilize CNN networks