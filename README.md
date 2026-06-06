# Flower Classification Using Transfer Learning (MobileNetV2 & ResNet50V2)

## Project Overview

This project focuses on flower image classification using transfer learning techniques and the Oxford Flowers 102 dataset.

Two pre-trained deep learning architectures were implemented and compared:

- MobileNetV2
- ResNet50V2

The project includes:

- Data preprocessing
- Data augmentation
- Transfer learning
- Fine-tuning
- Performance evaluation
- Confusion matrix analysis
- Error analysis

## Dataset

Oxford Flowers 102 Dataset

- 102 flower categories
- 8,189 images

Dataset source:
https://www.tensorflow.org/datasets/catalog/oxford_flowers102

## Results

### MobileNetV2

| Metric | Value |
|----------|----------|
| Accuracy | 73.13% |
| Precision | 73.64% |
| Recall | 74.22% |
| Macro F1 | 71.94% |

### ResNet50V2

| Metric | Value |
|----------|----------|
| Accuracy | 75.38% |
| Precision | 72.34% |
| Recall | 76.59% |
| Macro F1 | 73.19% |

## Best Model

Fine-Tuned ResNet50V2 achieved the highest performance.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## Authors

- Abd-Almajeed Assem Sultan
- Ruba Mohammad Sroor
