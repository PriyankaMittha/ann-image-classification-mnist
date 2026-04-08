## 🧠 ANN for Handwritten Digit Classification (MNIST)
## 📌 Project Overview

This project demonstrates the implementation of an Artificial Neural Network (ANN) using TensorFlow and Keras to classify handwritten digits (0–9) from the MNIST dataset. It includes model building, training, evaluation, and visualization of predictions.

## 🎯 Objectives

Build an ANN model for image classification
Understand forward and backward propagation
Apply activation functions and optimizers
Evaluate model performance
Visualize predictions

---

## 🛠️ Technologies Used
```
Python 3.10
TensorFlow (2.15.0)
Keras (built-in with TensorFlow)
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
```
---

## 📂 Dataset
```
MNIST Dataset
60,000 training images
10,000 testing images
Image size: 28 × 28 pixels
```
---

## 🧠 Model Architecture
```
Input Layer (28x28)
        ↓
Flatten Layer (784)
        ↓
Dense Layer (300 neurons, ReLU)
        ↓
Dense Layer (100 neurons, ReLU)
        ↓
Output Layer (10 neurons, Softmax)
```
---

## 🧠 What is ANN?

An Artificial Neural Network (ANN) is a deep learning model inspired by the human brain that learns patterns from data using layers of interconnected neurons.

---

## 🔄 Forward Propagation

Input data flows through layers to generate predictions.

---

## 🔁 Backpropagation

Errors are calculated and weights are updated to minimize loss.

---

## ⚙️ Activation Functions

**ReLU**: Used in hidden layers

**Softmax**: Used in output layer for probability distribution

**📉 Loss Function**: Sparse Categorical Crossentropy for multi-class classification

**⚡ Optimizer**: SGD (Stochastic Gradient Descent) used for training

**🧩 Flatten Layer**: Converts 2D image (28×28) into 1D vector (784)

---

## 📈 Results

- The model achieved good accuracy on training and testing data
- Successfully classified handwritten digits
- Visualization helped in understanding predictions

---

### 📌 Conclusion

The ANN model was successfully implemented using TensorFlow and Keras. It effectively learned patterns from the MNIST dataset and performed accurate classification. This project demonstrates key deep learning concepts such as forward propagation, backpropagation, activation functions, and optimization techniques.

--- 

## 📁 Project Structure
```
ann-image-classification-mnist/
│── ann_model.ipynb
│── README.md
│── requirements.txt
```
---

## 🤝 Connect with Me
```
💼 LinkedIn: https://www.linkedin.com/in/priyanka-mittha
💻 GitHub: https://github.com/PriyankaMittha
```
