# Neural Networks and Machine Learning Implementations

## Overview
This repository contains implementations of fundamental machine learning and neural network algorithms developed using **Python** and **NumPy**.

The main objective of these assignments is to understand the **core mathematical concepts behind machine learning models** by implementing them from scratch instead of using pre-built machine learning libraries.

The repository includes implementations of:

- Perceptron models for simulating logic gates
- Logistic Regression using a single-layer neural network
- Multiple Linear Regression
- Multilayer Perceptron (MLP) trained using the Backpropagation algorithm

These projects demonstrate how learning algorithms work internally and help build a strong foundation in neural networks.

---

## Assignment 1: Perceptron for Logic Gates

### Objective
Design and implement a perceptron model to simulate basic logic gates.

### Gates Implemented
- AND Gate
- OR Gate
- NAND Gate
- NOR Gate

### Description
A **perceptron** is one of the simplest neural network models used for solving binary classification problems.

In this assignment, appropriate weights and bias values are selected so that the perceptron reproduces the behavior of logical operations.

The perceptron computes:

y = f(w1x1 + w2x2 + b)

Where:

- x1, x2 → input values  
- w1, w2 → weights  
- b → bias  
- f → step activation function  

### Technologies Used
- Python
- NumPy

---

## Assignment 2: Logistic Regression using Single Layer Perceptron

### Objective
Implement logistic regression using a **single-layer perceptron neural network** for classification.

### Dataset
Glass Identification Dataset

Dataset Link:  
https://www.kaggle.com/datasets/uciml/glass

### Description
The Glass dataset contains information about the chemical composition of different types of glass.

Logistic regression is implemented using a **sigmoid activation function** and **gradient descent optimization** to classify glass samples.

### Steps Involved
1. Load the dataset
2. Preprocess and normalize the features
3. Train the model using gradient descent
4. Predict class labels
5. Evaluate model accuracy

### Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn (for preprocessing and train-test split)

---

## Assignment 3: Multiple Linear Regression using Perceptron

### Objective
Implement **multiple linear regression** using a perceptron-based learning approach.

### Dataset
Multiple Linear Regression Dataset

Dataset Link:  
https://www.kaggle.com/datasets/hussainnasirkhan/multiple-linear-regression-dataset

### Description
Multiple linear regression predicts a continuous output using multiple input variables.

The model learns optimal weights using **gradient descent** to minimize the prediction error.

General model:

y = w1x1 + w2x2 + ... + wnxn + b

### Steps Involved
1. Load the dataset
2. Normalize input features
3. Train the regression model
4. Predict test values
5. Compute **Mean Squared Error (MSE)**

### Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

---

## Assignment 4: Multilayer Perceptron with Backpropagation

### Objective
Implement a **Multilayer Perceptron (MLP)** and train it using the **backpropagation algorithm**.

### Dataset
Abalone Dataset

Dataset Link:  
https://archive.ics.uci.edu/dataset/1/abalone

### Description
The goal of this assignment is to predict the **age of abalone** based on physical measurements such as length, diameter, height, and weight.

The neural network architecture consists of:

- Input Layer
- Hidden Layer
- Output Layer

Backpropagation is used to update the network weights by minimizing the **Mean Squared Error (MSE)** between predicted and actual values.

### Steps Involved
1. Data preprocessing
2. One-hot encoding of categorical variables
3. Forward propagation
4. Loss computation
5. Backpropagation
6. Weight updates using gradient descent

### Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

---

## Requirements

Install the required Python libraries:

pip install numpy pandas scikit-learn

---

## How to Run

1. Clone the repository

git clone https://github.com/yourusername/repository-name.git

2. Download the required datasets

3. Run the Python scripts

Example:

python perceptron_logic_gates.py  
python logistic_regression_glass.py  
python multiple_linear_regression.py  
python mlp_backpropagation_abalone.py  

---

## Learning Outcomes

After completing these assignments, the following concepts can be understood:

- Perceptron learning algorithm
- Logistic regression using neural networks
- Multiple linear regression implementation
- Multilayer perceptron architecture
- Backpropagation algorithm
- Gradient descent optimization

---

## Author

**Prigya Goyal**  
Computer Engineering Student
