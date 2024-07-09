# Iris_Classification_NN
Iris classification Neural Network

# Iris Classification with Neural Networks

This project focuses on classifying the Iris flower species using a neural network model built with TensorFlow and Keras. The dataset used is the famous Iris dataset.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Iris dataset is a classic dataset in machine learning, consisting of 150 samples of iris flowers with four features each (sepal length, sepal width, petal length, petal width). The task is to classify each sample into one of three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Iris_Classification_NN.git
    cd Iris_Classification_NN
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS and Linux
    source venv/bin/activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To train and evaluate the model, run the main script:
```sh
python main.py
