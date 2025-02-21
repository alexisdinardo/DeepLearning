# Image Classification and Convolutional Neural Networks (CNNs)

## Overview
This project explores **image classification** using **Convolutional Neural Networks (CNNs)** in **PyTorch**. It involves working with a subset of the **SUN397 dataset**, performing **image preprocessing**, implementing **gradient-based optimization**, and training a **CNN** for scene classification.

## Features
- **Exploring the SUN Dataset**  
  - Work with a **subset of the SUN397 dataset** (20 categories, 50 images per category).
  - Use **PyTorch’s DataLoader** for image loading and manipulation.
  - Analyze dataset statistics (e.g., counting portrait-mode images per category).

- **Curve Fitting with PyTorch**  
  - Fit a **polynomial function** to given data points by optimizing four parameters.
  - Use **PyTorch autograd** for automatic differentiation.
  - Plot predictions against the original data.

- **Training a Convolutional Neural Network (CNN)**  
  - Implement a **CNN model** for scene classification.
  - Set up dataset preparation, **hyperparameters** (learning rate, batch size, optimizer, epochs), and train the model.
  - Evaluate performance using **validation accuracy**.

- **Making Predictions with the Trained CNN**  
  - Process input images and obtain **softmax probabilities** for different scene categories.
  - Display and interpret the model’s predictions.

## Technologies Used
- **Python**
- **PyTorch**
- **NumPy**
- **Matplotlib**


## Acknowledgments
This project is based on **CS 1674/2074: Image Classification and CNNs** coursework. The dataset is derived from the **SUN397 dataset**.

