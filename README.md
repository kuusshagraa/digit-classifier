# MNIST Digit Classifier: Neural Networks & Baselines

An exploration of handwritten digit recognition using the classic MNIST dataset. This repository contains various machine learning models built from scratch and using standard libraries, ranging from a simple heuristic baseline to fully custom-built neural networks and convolutional neural networks (CNNs). 

This project was heavily inspired by the architecture and mathematical foundations taught in Michael Nielsen's *Neural Networks and Deep Learning*.

## 🚀 Features & Models

This repository includes several different approaches to solving the MNIST classification problem:

* **`network.py`**: A custom, from-scratch Feedforward Neural Network built using only NumPy. Features custom implementations of Stochastic Gradient Descent (SGD), backpropagation, and sigmoid activations.
* **`conv.py`**: Convolutional Neural Network (CNN) architectures (including shallow nets, basic conv, and double conv with dropout) implemented using Theano.
* **`mnist_svm.py`**: A baseline Support Vector Machine (SVM) classifier implemented using `scikit-learn`.
* **`mnist_average_darkness.py`**: A naive, purely heuristic classifier that categorizes digits based solely on their average pixel darkness (useful as an absolute baseline).
* **`expand_mnist.py`**: A data augmentation utility script that artificially expands the training dataset by displacing images (up, down, left, right) by one pixel to improve model robustness.
* **`mnist_loader.py`**: A utility script to load and format the compressed MNIST dataset for training and testing.

## 🛠️ Prerequisites

To run these scripts, you will need Python installed along with the following libraries:
* `numpy`
* `scikit-learn`
* `Theano` 
* `matplotlib`

You can install the main dependencies via pip:
```bash
pip install numpy scikit-learn Theano matplotlib
