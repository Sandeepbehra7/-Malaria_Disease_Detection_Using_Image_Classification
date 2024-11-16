# -Malaria_Disease_Detection_Using_Image_Classification
 Malaria Disease Detection using Image Classification is a machine learning based project designed to automate the classification of malaria-infected and healthy cells using image data. Leveraging HOG for feature extraction and a variety of classifiers (SVM, Random Forest, etc.,), this project aims to aid in rapid malaria diagnosis.

# Malaria_Disease_Detection_Using_Image_Classification
## Overview
This project focuses on the classification of malaria-infected and healthy cell images using machine learning algorithms. The dataset consists of over 13,000 images divided into three categories: `Good`, `Bad`, and `Test`. The project applies various classification models to achieve optimal results and evaluate performance metrics.

## Dataset
- **Good**: Contains images of healthy cells.
- **Bad**: Contains images of malaria-infected cells.
- **Test**: Contains images used for testing the models.
- Images are stored in subfolders: `Good`, `Bad`, and `Test`.

## Features
- Utilizes **Histogram of Oriented Gradients (HOG)** for feature extraction.
- Implements multiple machine learning classifiers:
  - Support Vector Machine (SVM)
  - Naive Bayes
  - k-Nearest Neighbors (k-NN)
  - Random Forest
  - Decision Tree (J48)
  - AdaBoost
- Performance evaluation with metrics such as:
  - Accuracy Score
  - Confusion Matrix
- Visualizes confusion matrices using Seaborn heatmaps.

## Requirements
The project requires the following Python libraries:
- `opencv-python`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scikit-image`

To install all dependencies:
```bash
pip install -r requirements.txt
