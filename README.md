# Stroke Detection Through Stacked Ensemble Learning

## Overview
The goal of this project is to detect strokes using a robust machine learning model that combines multiple algorithms in a stacked ensemble framework. By addressing limitations in data quality and applying optimization techniques, the project aims to provide accurate and reliable predictions.

## Key Methodology

### 1. Data Collection and Preprocessing
Data preprocessing is a crucial step in ensuring the accuracy and robustness of the models. It involves several key tasks:
- **Removing Unnecessary Columns:** Dropping irrelevant data to streamline the dataset.
- **Handling Missing Values:** Replacing missing values in columns like `bmi` with the mean.
- **Outlier Detection and Removal:** Using the Interquartile Range (IQR) method to identify and eliminate outliers.
- **Data Encoding, Scaling, and Balancing:** Preparing the data for machine learning models through normalization, encoding categorical data, and balancing classes.

**Data Preprocessing Workflow:**

### 2. Data Splitting
The dataset is split into training and testing sets to evaluate the model's performance. This split ensures the model is trained on one portion of the data and tested on unseen data to gauge its generalizability.

### 3. Model Selection
Multiple machine learning algorithms are tested and evaluated. The most effective models are combined into a stacked ensemble, enhancing overall prediction accuracy. Model performance is evaluated both before and after optimization.

### 4. Model Optimization
Optimization techniques, such as Grid Search and Random Search, are used to fine-tune model hyperparameters. The objective is to maximize the performance of individual models before combining them into the final ensemble.

### 5. Model Evaluation
The models are rigorously evaluated using metrics like:
- **Accuracy**
- **AUC (Area Under the Curve)**
- **Precision, Recall, and F1-Score**

Models are compared based on performance metrics before and after optimization to ensure the improvements are significant and impactful.

![image](https://github.com/user-attachments/assets/e238562d-60a8-4bb4-ab3d-a32806da997d)

