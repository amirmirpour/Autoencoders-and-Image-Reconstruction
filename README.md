# Autoencoders and Image Reconstruction

This project explores neural networks for image classification, representation learning, and image reconstruction using PyTorch.

## Overview

The notebook covers the following topics:

- **MNIST Classification:** Training a fully connected neural network to classify handwritten digits.
- **Autoencoders:** Learning compressed latent representations and reconstructing images.
- **Denoising Autoencoders:** Reconstructing images from corrupted inputs.
- **Convolutional Autoencoders:** Applying convolutional neural networks to image reconstruction using CIFAR-10.
- **Model Evaluation and Visualization:** Analyzing training history, confusion matrices, and learned representations using PCA and t-SNE.

## Datasets

- **MNIST:** Handwritten digit images.
- **CIFAR-10:** Color images from ten object categories.

The datasets are downloaded automatically using `torchvision`.

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## How to Run

1. Clone or download this repository.
2. Install the required dependencies.
3. Open `AutoEncoders.ipynb` in Jupyter Notebook or VS Code.
4. Select the appropriate Python environment and run the cells in order.

The notebook automatically uses a CUDA-enabled GPU when available; otherwise, it runs on the CPU.
