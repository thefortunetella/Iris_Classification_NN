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
```

## Model Architecture

The neural network model has the following architecture:

Input Layer: 4 features
Hidden Layer 1: 32 neurons, ReLU activation
Hidden Layer 2: 64 neurons, ReLU activation
Output Layer: 3 neurons (one for each class), Softmax activation
The model is compiled with the categorical cross-entropy loss function and the RMSprop optimizer.

## Results

During training, the model's performance improves over 10 epochs. 

**Accuracy:**

- Represents the proportion of correct predictions made by the model on the training dataset.
- Accuracy started at 67.5% in the first epoch and increased to 84.17% by the tenth epoch.

**Val_accuracy (Validation Accuracy):**

- Represents the proportion of correct predictions on the validation dataset.
- Started at 86.67% and ended at 86.67%, indicating consistent performance.

**Loss:**

- Represents the penalty associated with incorrect predictions made by the model.
- Loss decreased from 1.0450 in the first epoch to 0.3980 in the tenth epoch, showing that the model is learning and correctly adjusting its parameters.

**Val_loss (Validation Loss):**

- Represents the penalty associated with incorrect predictions on the validation dataset.
- Validation loss started at 0.9886 and decreased to 0.3829, indicating an improvement in the model's performance on the validation set.

### Considerations

**Evolution of Accuracy and Loss:**

- The model is improving in terms of both accuracy and loss over the epochs, which is a good sign.

**Consistency between Training and Validation:**

- The accuracy and validation loss are consistent with those of the training, suggesting that the model is not suffering from overfitting or underfitting.

