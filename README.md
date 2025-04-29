# Face Emotion Recognition using CNN

## Overview
This project builds a deep learning model using Convolutional Neural Networks (CNN) to classify facial expressions into different emotion categories. These categories include surprise, fear, sadness, disgust, contempt, happiness, and anger. The model is trained on an image dataset and achieves high accuracy and F1-score on validation data.

## Final Model Performance
**Epoch 50/50 Results:**
- **F1 Score**: 0.9774 (train), 0.9896 (validation)
- **Accuracy**: 97.75% (train), 98.98% (validation)
- **Loss**: 0.0576 (train), 0.0704 (validation)

## Model Architecture
The CNN model consists of:
- 3 convolutional layers with ReLU activation and max-pooling
- Dropout layers to reduce overfitting
- Fully connected layers with softmax activation for multi-class classification

## Training Process
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Metrics**: Accuracy, Weighted F1 Score
- **Epochs**: 50

## Performance Evaluation
Model performance was evaluated using:
- Loss vs. Accuracy plots for training and validation
- F1 Score trend over epochs
- Confusion Matrix for analyzing misclassifications

