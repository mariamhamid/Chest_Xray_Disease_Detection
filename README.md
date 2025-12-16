# Chest_Xray_Disease_detection


A deep learning project to classify chest X-ray images as Normal or Pneumonia.

# Project Overview

This project applies Convolutional Neural Networks (CNNs) to detect pneumonia from chest X-ray images. The model is trained on labeled radiographic data to support automated and accurate pneumonia detection.



# Dataset
- **Source:** [Chest X-Ray Images (Pneumonia) – Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

# Dataset Structure

```text
data/
└── chest_xray/
    ├── train/
    │   ├── NORMAL/
    │   └── PNEUMONIA/
    ├── val/
    │   ├── NORMAL/
    │   └── PNEUMONIA/
    └── test/
        ├── NORMAL/
        └── PNEUMONIA/
``` 



# Model Performance

| Class       | Precision | Recall | F1-score | Support |
|------------|-----------|--------|----------|--------|
| NORMAL     | 0.89      | 0.80   | 0.84     | 234    |
| PNEUMONIA  | 0.89      | 0.94   | 0.91     | 390    |

- **Accuracy:** 0.89  
- **Weighted F1-score:** 0.89

# Results
-The model achieves 89% accuracy on the test set.
-High recall for PNEUMONIA ensures fewer missed cases.
-Balanced precision across both classes indicates reliable predictions.


# Next Steps / Future Improvements

- Experiment with data augmentation techniques to improve model generalization and robustness.  
- Evaluate advanced CNN architectures such as ResNet and EfficientNet to enhance performance.  
- Deploy the trained model as a web or mobile application for real-world usage.  
- Extend the system to multi-class classification to detect additional lung diseases.  
- Integrate Explainable AI (XAI) methods (e.g., Grad-CAM) to visualize and interpret model predictions.
