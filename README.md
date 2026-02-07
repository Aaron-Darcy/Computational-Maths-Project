# Computational-Maths-Project
# Heart Disease Prediction Using a Neural Network From Scratch (NumPy)

This project implements a complete feed-forward neural network using only **NumPy** to predict whether a patient has heart disease from clinical features.  
No machine learning libraries are used (no TensorFlow, PyTorch, Scikit-Learn, SciPy).

## Project Highlights
- Manual preprocessing:
  - binary categorical encoding (0/1)
  - manual one-hot encoding
  - standardisation of continuous features
- Neural network built from scratch:
  - forward propagation
  - backpropagation (chain rule)
  - gradient descent optimisation
  - sigmoid activations
  - binary cross-entropy loss
- Early stopping using a validation split to reduce overfitting

## Model Architecture
Input → 16 neurons → 8 neurons → 1 output neuron (sigmoid)

## Dataset
The notebook expects a `heart.csv` dataset (clinical features + target label).  
Dataset Used: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

## How to Run
1. Open the notebook:
   - `Heart_Disease_NN_From_Scratch.ipynb`
2. Run all cells in order.

Recommended environment:
- Python 3.x
- NumPy
- Matplotlib

Install dependencies:
```bash
pip install numpy matplotlib

