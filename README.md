# Crowd Detection using CV

### Project Overview:

This project focuses on classifying places as crowded or non-crowded to assist visually impaired individuals in navigating their surroundings. The system uses image processing and machine learning techniques to analyze images and detect the presence of crowds.

### Key Components:
1. Data Preprocessing

 - Image Resizing – Standardized all images for uniformity

 - Grayscale Conversion – Simplified images to reduce computational complexity

 - Histogram Equalization – Improved contrast for better feature extraction

2. Feature Extraction

 - SIFT (Scale-Invariant Feature Transform):
   - Extracted key features invariant to scale and rotation

 - Dimensionality Reduction:
   - Reduced feature space using PCA for better computational efficiency

3. Classification

 - Multiple machine learning classifiers were trained and evaluated:

   - Support Vector Machine	
   - Random Forest	
   - K-Nearest Neighbors
   - Decision Tree	
   - Logistic Regression

 - Random Forest classifier resulted in an accuracy of 83.22%

### Technologies Used:

 - Python

 - OpenCV – For image preprocessing and SIFT feature extraction

 - Scikit-learn – For machine learning models and evaluation

### Features:

 - Crowd detection through image classification

 - SIFT-based feature extraction pipeline

 - Evaluation using accuracy, precision, recall, and F1 score

 - Designed for assistive technology applications


Link to the dataset : https://drive.google.com/drive/folders/1-rUfOo3d-FGsb7si3mUwA_prOiAK4usc?usp=sharing
