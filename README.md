# Crowd Detection Using CV

## Overview:
In public spaces, the inability to perceive crowd density poses a significant risk to individuals with visual impairments. This project addresses that challenge by developing a real-time crowd detection system, enabling safer navigation through the environment.

## Objective:
 - To design a reliable and efficient system that detects crowded versus non-crowded environments from images and provides actionable alerts to assist visually impaired users in making safer mobility decisions.

## Key Features:
 - Real-Time Crowd Detection:
   - Utilizes computer vision techniques to classify crowd levels in real-time.

 - High Accuracy Classification:
   - Achieved highest accuracy using SVM, outperforming classifiers like KNN, Random Forest, Decision Tree, and Logistic Regression.

 - Assistive Integration:
   - Designed for future integration with wearable devices to provide audio or haptic feedback to the user.

 - Multi-Classifier Evaluation:
   - Benchmarked multiple ML models to ensure optimal performance across different scenarios.

## Methodology:
 - Data Collection & Preprocessing:
   - Compiled a dataset of images labeled as crowded or non-crowded.

   - Applied preprocessing steps including resizing, grayscale conversion, and histogram equalization.

 - Feature Extraction:
   - Used SIFT (Scale-Invariant Feature Transform) to extract robust visual features.

   - Reduced feature dimensions with Principal Component Analysis (PCA) to enhance model efficiency.

 - Model Training & Evaluation:
   - Trained multiple classifiers including SVM, Random Forest, KNN, Decision Tree, and Logistic Regression.

   - Evaluated models using accuracy, precision, recall, and F1-score.

## Results:
 - The system achieved high accuracy with SVM for crowd classification.

 - Demonstrated potential for real-time crowd awareness assistance for visually impaired individuals.

## Future Work:
 - Dataset Expansion: Incorporate varied crowd types, perspectives, and lighting conditions.

 - Real-World Testing: Conduct user trials to validate system usability in live environments.


Link to the dataset : https://drive.google.com/drive/folders/1-rUfOo3d-FGsb7si3mUwA_prOiAK4usc?usp=sharing
