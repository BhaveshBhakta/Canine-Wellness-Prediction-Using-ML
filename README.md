# Canine Wellness Prediction

## Project Overview

This project aims to build a predictive machine learning pipeline to assess the health status of dogs using synthetic wellness data. The dataset includes a wide range of features such as breed, diet, activity level, medical history, and environmental factors. The core objective is to identify whether a dog is healthy or not based on various lifestyle and physiological indicators.

## Technical Highlights

* **Dataset**: 10,000 synthetic records (6,000 used for modeling) from [Kaggle](https://www.kaggle.com/datasets/aaronisomaisom3/canine-wellness-dataset-synthetic-10k-samples)
* **EDA**: Histograms, boxplots, correlation heatmaps for exploratory analysis
* **Preprocessing**:

  * Null handling via mean/mode imputation
  * Label encoding of categorical variables
  * SMOTE for class balancing
* **Models Used**:

  * Logistic Regression, Ridge Classifier
  * Decision Trees, Random Forest, AdaBoost, Gradient Boosting, Bagging
  * XGBoost, SVM
* **Evaluation**:

  * Accuracy, Precision, Recall, F1-Score
  * Confusion matrix visualization per model

## Purpose and Applications

This project serves as a baseline for:

* Early health risk prediction in veterinary applications
* Personalizing pet care based on behavioral and physiological data
* Exploring synthetic data modeling in animal health analytics

## Installation

 **Clone the repository**

   ```bash
   git clone https://github.com/BhaveshBhakta/Canine-Wellness-Prediction-Using-ML.git
   cd Canine-Wellness-Prediction-Using-ML
   ```

## Collaboration

Contributions are welcome. If you'd like to suggest improvements, fix bugs, or extend the functionality.

