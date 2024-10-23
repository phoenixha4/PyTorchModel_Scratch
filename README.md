# PyTorchModel_Scratch
## Image Classifier for Playing Cards Using PyTorch

## Overview

This project implements an image classifier to detect playing cards using PyTorch. It involves three main parts:

1. **Dataset Preparation**: Loads and transforms the card image dataset using `PyTorch Dataset` and `Dataloader`.
2. **Model Creation**: Builds a custom image classifier using a pre-trained `EfficientNet` model, fine-tuned for 53 classes of playing cards.
3. **Training and Evaluation**: Trains the model and evaluates its performance on test images.

## Key Details

- **Training Setup**:
  - **Loss Function**: Cross-Entropy Loss
  - **Optimizer**: Adam
  - **Epochs**: 5
  
- **Results**:
  - **Train loss**: 0.20249637958651326
  - **Validation loss**: 0.15745035499896642
  - The model predicts card classes with probabilities, and results are visualized with bar plots.

This project serves as a practical learning experience to understand PyTorch in detail.
