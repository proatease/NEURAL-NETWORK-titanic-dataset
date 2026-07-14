# Neural Networks from Scratch using NumPy

This repository documents my journey of learning the fundamentals of neural networks by implementing machine learning algorithms completely from scratch using **NumPy**, without relying on deep learning frameworks like TensorFlow or PyTorch.

The project starts with Logistic Regression, progresses to a Shallow Neural Network, and finally implements a configurable Deep Neural Network using forward propagation, backpropagation, and gradient descent.

## Project Goals

* Understand how neural networks work internally
* Implement every mathematical operation manually
* Learn forward propagation and backpropagation
* Understand activation functions and loss functions
* Gain intuition behind weight updates and gradient descent
* Compare simple and deeper neural network architectures

---

## Implementations

### 1. Logistic Regression

Implemented binary logistic regression from scratch using:

* Sigmoid activation
* Binary Cross-Entropy Loss
* Gradient Descent
* Manual gradient computation
* Weight and bias optimization

Dataset:

* Titanic Survival Prediction

---

### 2. Shallow Neural Network

Implemented a neural network with:

* One hidden layer
* Sigmoid activation
* Manual forward propagation
* Manual backpropagation
* Weight updates using gradient descent

Features:

* Standardized input features
* Binary classification
* Accuracy and loss evaluation
* Hidden layer representation learning

---

### 3. Deep Neural Network

Built a configurable deep neural network supporting multiple layers.

Features include:

* Multiple fully connected layers
* Leaky ReLU hidden activation
* Sigmoid output activation
* He Weight Initialization
* Forward propagation
* Backpropagation
* Binary Cross-Entropy Loss
* Gradient Descent optimization

The implementation uses dictionaries to store weights, biases, activations, and gradients, making it easy to extend to deeper architectures.

---

## Dataset

The Titanic Survival dataset was used throughout the project.

Preprocessing includes:

* Handling missing values
* Encoding categorical features
* Feature standardization
* Train/Test split
* Binary target prediction

---

## Neural Network Concepts Covered

* Logistic Regression
* Binary Classification
* Sigmoid Activation
* Leaky ReLU Activation
* Forward Propagation
* Backpropagation
* Gradient Descent
* Binary Cross Entropy Loss
* Weight Initialization
* Feature Scaling
* Hidden Layers
* Deep Neural Networks
* Model Evaluation
* Prediction Thresholding

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn (StandardScaler)


---

## Learning Outcomes

Through this project I learned:

* The mathematics behind neural networks
* How gradients are computed during backpropagation
* How activation functions influence learning
* Why feature normalization is important
* How hidden layers improve model performance
* The differences between logistic regression, shallow neural networks, and deep neural networks
* How modern deep learning frameworks automate these operations

This repository focuses on understanding the core principles of deep learning rather than achieving state-of-the-art performance.

---

## Future Improvements

* Mini-batch Gradient Descent
* Adam Optimizer
* Regularization (L1/L2)
* Dropout
* Softmax for Multi-class Classification
* Model Saving and Loading
* Early Stopping
* Learning Rate Scheduling
* NumPy-based Mini Deep Learning Framework

---

## Author

**Pratisthit Raj Baral**

Computer Engineering Student passionate about Machine Learning, Deep Learning, and Computer Vision.

GitHub: https://github.com/proatease
