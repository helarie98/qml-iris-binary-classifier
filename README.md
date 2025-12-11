# QUANTUM MACHINE LEARNING PROJECT: BINARY CLASSIFICATION ON THE IRIS DATASET (A QClass23/24 Assignment – QWorld)

## 🌱 Project Overview

This project implements a quantum machine learning (QML) model using PennyLane to classify the first two classes of the Iris dataset: Setosa, Versicolor. The model uses quantum circuits, differentiable programming, and classical optimization techniques to perform binary classification based on sepal and petal features. This work was completed as part of the QClass23/24 Quantum Machine Learning Task provided by QWorld.

## 🧠 Objectives

The goal of this project is to:

- Build a QML model using PennyLane

- Encode classical data into quantum states

- Train a binary classifier

- Explain model choice, encoding strategy, cost function, and optimization method

- Demonstrate results in a clear, reproducible notebook

## 📓 Notebook

All implementation and explanations are inside:

👉 Notebook

This includes:

Data preparation and data ploting

Quantum circuit design

Data encoding method

Cost function selection

Optimizer choice

Training loop

Evaluation metrics


## 🧩 Model Summary

The QML Model used here is a variational quantum circuit implemented with PennyLane, using:

- A data-encoding layer

- Trainable rotational layers

- Entangling operations


## Encoding Method

The features are encoded using Angle embedding

## Cost Function: 
Mean squared error (MSE) 

##Optimization Method: 
Gradient Descent Optimizer

## 📦 Installation

To reproduce the results: git clone https://github.com/<helarie98>/<qml-iris-binary-classifier>.git
cd <qml-iris-binary-classifier>

pip install -r requirements.txt

## ▶️ Running the Notebook
jupyter notebook: Notebook/qml_iris_classifier.ipynb

## 📚 References

* PennyLane tutorials: https://pennylane.ai/qml/demonstrations/

* https://www.nature.com/articles/s41598-023-46469-2#Tab1

* https://github.com/sophchoe/Binary_Classification_Pennylane_Keras

* https://doi.org/10.1038/s41598-023-46469-2

* QClass23/24 materials

## 📄 License

This project is released under the MIT License.
