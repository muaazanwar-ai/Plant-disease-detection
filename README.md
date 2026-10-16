# Plant Disease Detection Using MobileNetV2

## Project Overview
This project uses deep learning to classify plant leaf images into 15 plant disease and healthy-leaf categories.

## Dataset
- **Dataset:** PlantVillage
- **Source:** [Kaggle PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- **Images loaded:** 20,638
- **Classes:** 15

## Methodology
- Image resizing: 224 × 224 pixels
- Data augmentation: Random horizontal flipping and rotation
- Model: MobileNetV2 with ImageNet pretrained weights
- Framework: TensorFlow / Keras
- Dataset split: 80% training and 20% validation

## Initial Results
- Training epochs: 5
- Training accuracy: 89.71%
- Validation accuracy: 90.87%
- Weighted F1-score: approximately 0.91

These are initial validation results, not independent test-set results.

## Project Features
- Plant leaf image classification
- Training and validation accuracy/loss graphs
- Confusion matrix and classification report
- Sample image prediction

## Limitations
The model can misclassify individual images. Its predictions should not be treated as a definitive plant-health diagnosis.

## Team Members
- Ahmad Saeed
- Rehan Ahmad
- Muaaz Anwar
