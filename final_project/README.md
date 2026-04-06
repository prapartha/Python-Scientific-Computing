# Final Project – MNIST Handwritten Digit Recognition

## Overview

A feedforward neural network trained on the MNIST dataset to classify handwritten digits (0–9), implemented in Keras with a TensorFlow backend.

**Notebook:** `keras_mnist_digit_recognition.ipynb`

---

## Dataset

The [MNIST database](http://yann.lecun.com/exdb/mnist/) is a standard benchmark in machine learning:
- **Training set:** 60,000 grayscale images (28×28 pixels)
- **Test set:** 10,000 grayscale images
- **Labels:** Integer digits 0–9
- **Loaded via:** `keras.datasets.mnist`

---

## Approach

1. **Load data** — `mnist.load_data()` returns `(X_train, y_train)` and `(X_test, y_test)`
2. **Preprocess** — Flatten 28×28 images to 784-element vectors; normalize pixel values to [0, 1]
3. **One-hot encode** labels using `keras.utils.to_categorical`
4. **Build model** — Dense feedforward network with ReLU activations and softmax output
5. **Train** — Minimize categorical cross-entropy with the Adam optimizer
6. **Evaluate** — Report accuracy on the held-out test set
7. **Visualize** — Display sample predictions and network architecture diagram

---

## Requirements

```bash
pip install tensorflow keras matplotlib numpy pydot graphviz
```

## Running

Open and run `keras_mnist_digit_recognition.ipynb` in Jupyter.

```bash
jupyter notebook keras_mnist_digit_recognition.ipynb
```

---

## Reference

Feedforward network structure follows the tutorial by Vict0rSch:
https://github.com/Vict0rSch/deep_learning/tree/master/keras/feedforward
