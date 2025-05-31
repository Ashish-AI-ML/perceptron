# 🧠 Perceptron: A Foundational Neural Network

## Overview

The **Perceptron** is the most fundamental type of artificial neural network, introduced by **Frank Rosenblatt in 1958**. It is a **supervised learning algorithm** designed for **binary classification tasks**. This repository explains the working principles, components, and uses of a Perceptron, and how it forms the foundation of more complex neural networks.

---

## 🔧 How It Works

A Perceptron maps input features to a binary output using a **linear decision boundary**:

\[
\text{Output} = 
\begin{cases}
1 & \text{if } w \cdot x + b \geq 0 \\
0 & \text{otherwise}
\end{cases}
\]

- **w**: weights
- **x**: input features
- **b**: bias
- **Activation Function**: Step function (binary output)

---

## 📦 Components

| Component       | Description                                         |
|----------------|-----------------------------------------------------|
| **Inputs (x)**  | Feature vector                                      |
| **Weights (w)** | Importance of each input feature                   |
| **Bias (b)**    | Adjusts the threshold for classification            |
| **Activation**  | Step function for decision-making                   |
| **Output**      | Predicted class: 0 or 1                             |

---

## ✅ Use Cases

Although limited to linearly separable problems, Perceptrons serve as the basis for deep learning systems.

- Binary classification (e.g., spam detection)
- Logic gates simulation (AND, OR, NAND)
- Basic image recognition tasks
- Sentiment analysis (binary outcomes)
- Educational tool for understanding neural networks

---

## ⚠️ Limitations

- Only handles **linearly separable** datasets
- Cannot solve problems like **XOR** without multilayer networks

---

## 🚀 From Perceptron to Deep Learning

The simple Perceptron model evolved into:
- **Multi-Layer Perceptrons (MLPs)**
- **Backpropagation algorithms**
- **Modern Deep Neural Networks (DNNs)**

---

## 📂 Folder Structure

