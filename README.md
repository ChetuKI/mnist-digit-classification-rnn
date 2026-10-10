# MNIST Digit Classification using RNN

## Overview
This project implements a Recurrent Neural Network (RNN) using PyTorch to classify handwritten digits from the MNIST dataset. Each 28×28 image is treated as a sequence of 28 rows, with each row containing 28 pixel values.

## Technologies Used
- Python
- PyTorch
- Torchvision
- MNIST Dataset

## Model Architecture
- **Input Size:** 28
- **Hidden Size:** 128
- **Number of RNN Layers:** 1
- **Output Classes:** 10 (digits 0–9)
- **Loss Function:** Cross-Entropy Loss
- **Optimizer:** Adam

## Dataset
The MNIST dataset contains grayscale images of handwritten digits from 0 to 9. It is loaded using `torchvision.datasets.MNIST`.

Dataset reference: [MNIST Database](https://www.tensorflow.org/datasets/catalog/mnist)

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install torch torchvision
   ```
3. Open `RNN_for_hw_digit_classification.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to train and evaluate the model.

## Results
The model is evaluated on the MNIST test dataset using classification accuracy.

## Author
**Chetan Kallappa Ingali**
