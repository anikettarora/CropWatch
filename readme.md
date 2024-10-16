# Crop Watch 🌱

Crop Watch is a plant disease detection system that utilizes a Convolutional Neural Network (CNN) model for early detection and better crop management. This project aims to help farmers and agricultural professionals identify plant diseases quickly and accurately to improve crop yields and reduce losses.

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Early Disease Detection**: Classifies plant diseases with high accuracy for proactive crop management.
- **User-Friendly Interface**: Intuitive design to facilitate easy interaction for users.
- **Scalable Model**: Designed for efficiency, suitable for real-world applications in agriculture.

## Architecture
The architecture of the Crop Watch system includes:

- **Image Processing**: Images are resized to 128x128 pixels and converted into arrays suitable for CNN input.
- **Convolutional Neural Network**: The model consists of multiple Conv2D and MaxPooling2D layers for feature extraction, alongside Dropout layers to prevent overfitting.
- **Training Phase**: 
  - Utilizes the Adam optimizer with a learning rate set for efficient training.
  - Trains over 10 epochs with a batch size of 32, minimizing error between predicted and actual outputs.
  - Employs a softmax layer for converting raw outputs into class probabilities.
- **Performance Analysis**: The model is assessed using a test set to evaluate its generalization capabilities on unseen data.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/anikettarora/CropWatch.git
   cd CropWatch
