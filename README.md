# Brain Tumor Detection from MRI using CNN and Transfer Learning
## Overview
This project presents an end-to-end deep learning system for detecting brain tumors from MRI images using a Custom Convolutional Neural Network (CNN) and Transfer Learning with EfficientNetB0.

The objective is to build an automated medical image classification model that can assist in early tumor detection and support clinical decision-making. Two models were implemented and compared:
- Custom CNN (Baseline Model)  
- Transfer Learning using EfficientNetB0

## Problem Statement
Brain tumors are life-threatening and require early and accurate diagnosis. Manual MRI analysis can be time-consuming and prone to human error. This project aims to develop a deep learning-based automated classification system for detecting brain tumors from MRI scans to improve diagnostic efficiency and reliability.

## Methodology

### Data Preprocessing
- Image resizing  
- Pixel normalization  
- Data augmentation to reduce overfitting  

### Exploratory Data Analysis
- Class distribution analysis  
- Sample MRI visualization  
- Image dimension inspection  

### Model Development

#### Custom CNN (Baseline Model)
- Convolution layers  
- ReLU activation  
- MaxPooling layers  
- Fully connected layers  
- Sigmoid/Softmax output layer
- 
#### Transfer Learning (EfficientNetB0)
- Pre-trained EfficientNetB0 model  
- Feature extraction  
- Fine-tuning  
- Performance comparison with baseline CNN  

## Model Evaluation
The models were evaluated using the following metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC Curve  
- ROC-AUC Score  

Transfer Learning demonstrated improved generalization and superior performance compared to the baseline CNN model.
## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  
- Visual Studio Code  

## Conclusion
This project demonstrates the practical application of deep learning and transfer learning techniques in medical image classification. The EfficientNetB0-based model provides improved accuracy and robustness for automated brain tumor detection from MRI scans.
