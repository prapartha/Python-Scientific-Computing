# Python for Scientific Computing

**Stony Brook University | Spring 2021**
**Student:** Pradhyumna Parthasarathy
**Program:** M.S. Physics

---

## Overview

Course materials and project work for a graduate-level scientific computing course using Python. The course progressively covers Python fundamentals, scientific visualization, numerical methods, and machine learning — all through hands-on Jupyter notebooks.

**Topics covered:**
- Python functions, list comprehensions, exception handling
- Object-oriented programming (classes and methods)
- Data visualization with **Matplotlib** (log-log plots, subplots, parametric curves)
- Numerical integration with **SciPy** (Simpson's rule, error analysis)
- Linear algebra and condition numbers with **NumPy/SciPy**
- Signal processing and Fourier analysis
- Deep learning with **Keras / TensorFlow** (neural networks, MNIST)

---

## Repository Structure

```
Python-Scientific-Computing/
├── exercises/
│   └── week3_python_basics.ipynb   # Python fundamentals: functions, primes,
│                                   # exception handling, tic-tac-toe game
├── final_project/
│   └── keras_mnist_digit_recognition.ipynb  # MNIST handwritten digit classifier
└── data/
    ├── nasa-giss.txt               # NASA GISS global temperature anomaly data
    └── shore_leave.txt             # Star Trek TOS transcript (text analysis)
```

---

## Exercises

### Week 3 – Python Basics (`exercises/week3_python_basics.ipynb`)

| Problem | Description |
|---|---|
| Q1 – Function Practice | Generalize a word-length filter function with a parameter `n` |
| Q2 – Prime Numbers | Find all primes up to N using trial division |
| Q3 – Exception Handling | Write `convert_type(a)` to safely cast strings to float/int |
| Q4 – Tic-Tac-Toe | Complete a 2-player game using provided helper functions |

---

## Final Project

### MNIST Digit Recognition with Keras (`final_project/keras_mnist_digit_recognition.ipynb`)

A feedforward neural network that classifies handwritten digits (0–9) from the MNIST dataset.

- **Dataset:** 60,000 training images + 10,000 test images (28×28 grayscale)
- **Framework:** Keras with TensorFlow backend
- **Architecture:** Dense feedforward network
- **Tasks:** Data loading and preprocessing, model construction, training, evaluation, visualization

---

## Environment

```bash
pip install tensorflow keras matplotlib numpy scipy pydot
```

Notebooks are designed to run in **Jupyter Lab** or **Jupyter Notebook**.

---

## Data Files

| File | Description |
|---|---|
| `nasa-giss.txt` | Annual global temperature anomalies (NASA GISS Surface Temperature Analysis) |
| `shore_leave.txt` | Text transcript of Star Trek TOS "Shore Leave" — used for word frequency analysis |
