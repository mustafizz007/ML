# Brain Tumor Classification using Machine Learning

This project focuses on classifying brain MRI images into four categories using
traditional machine learning techniques.

## Dataset
- Brain Tumor MRI Dataset (Kaggle)
- Classes: Glioma, Meningioma, Pituitary, No Tumor

## Objective
To build a multi-class classification model that can accurately classify brain
tumor types from MRI images using interpretable and computationally efficient
machine learning models.

## Methods Used
- Image resizing and grayscale conversion
- Feature extraction (mean, standard deviation, variance, histogram)
- Feature selection using Random Forest importance
- Dimensionality reduction using PCA
- Models: Random Forest, SVM

## Results
- Random Forest accuracy: ~91–93%
- Random Forest + PCA (10 components): ~90.85%
- 5-Fold Cross-Validation average accuracy: ~86.5%

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## References
- Kaggle Brain Tumor MRI Dataset
