# AI Tools F26 — CIFAR-10 Image Classification with MobileNet

This repository contains the implementation for a final project in Tools of Artificial Intelligence. The project investigates image classification on the CIFAR-10 dataset using a MobileNetV1 architecture.The focus is not only on achieving high accuracy, but also on understanding the full deep learning pipeline for image classification.

## Dataset

CIFAR-10 consists of 60,000 RGB images with a resolution of 32 × 32 pixels. The dataset contains 10 classes: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck.

## Implementation

The general pipeline is:

1. Dataset loading
2. Data augmentation
3. Training
4. Evaluation

## Requirements

The project is implemented in Python using PyTorch. Required packages:

```bash
!pip install torch torchvision numpy matplotlib scikit-learn pandas
```
