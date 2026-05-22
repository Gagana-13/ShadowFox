# Image Classification using Transfer Learning

## Project Overview
This project implements an Image Classification System using Transfer Learning with MobileNetV2 in TensorFlow. The model is trained to classify images into three categories:

- Cat
- Dog
- Car

The project uses a pre-trained MobileNetV2 model trained on ImageNet and applies transfer learning techniques to achieve high accuracy with a small custom dataset.

---

## Features
- Image classification using Deep Learning
- Transfer Learning with MobileNetV2
- Data Augmentation to reduce overfitting
- Accuracy visualization using Matplotlib
- Automatic dataset loading
- High validation accuracy

---

## Technologies Used
- Python
- TensorFlow
- MobileNetV2
- NumPy
- Matplotlib

---

## Dataset Structure

Organize the dataset in the following format:

dataset/
│
├── cat/
├── dog/
└── car/

Each folder should contain corresponding images.

---

## Installation

Install the required libraries:

```bash
pip install tensorflow matplotlib numpy