## 📌 Overview
This project implements a *feedforward neural network from scratch* using only *NumPy*, to classify handwritten digits (MNIST dataset).  
No TensorFlow. No Keras. Just raw math, matrix operations, and gradients.

## 🧩 Architecture
- Input Layer: 784 nodes (28×28 flattened image)
- Hidden Layer 1: 64 neurons — ReLU
- Hidden Layer 2: 32 neurons — ReLU
- Output Layer: 10 neurons — Softmax
- Loss: Categorical Cross-Entropy
- Optimizer: Gradient Descent (manual implementation)

## 🚀 Training
- Dataset: MNIST (60,000 train, 10,000 test)
- Epochs: 10  
- Learning Rate: 0.0001  
- Accuracy: *94.19% (test set)*

## 📊 Results
- *Loss curve* shows clear convergence
- *Confusion matrix* and *classification report* validate performance
- *Visualization of predictions* for sample digits

## 🔬 Concepts Covered
- Forward propagation (matrix dot products, bias addition)
- ReLU and Softmax activations
- Backpropagation (manual gradient calculation)
- Weight and bias updates using gradient descent

## 🧾 Visuals
- 📉 Loss vs. Epoch plot
- 📊 Confusion Matrix (MNIST digits)
- 🖼 Random Predictions Display

## 🛠 Dependencies
```bash
numpy
matplotlib
scikit-learn
