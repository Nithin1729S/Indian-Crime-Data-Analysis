# Crime Data Analysis

This repository contains scripts and notebooks for analyzing crime data using various machine learning algorithms.

## Algorithms Used

- **Linear Regression**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**
- **Naive Bayes**
- **Clustering (K-Means, Hierarchical, DBSCAN)**

## How it Works

### 1. Data Loading and Preprocessing

- Crime data is loaded from a CSV file.
- Data is cleaned and encoded for categorical variables.

### 2. Linear Regression

- Predicts 'TOTAL IPC CRIMES' using other crime statistics.
- **Performance Metrics:**
  - R-squared: 0.9999999999452605
  - Mean Absolute Error: 0.006192793043933714
  - Mean Squared Error: 0.02750475477950661

### 3. Logistic Regression

- Classifies crime levels based on various crime types.
- **Accuracy:** 0.9925474254742548

### 4. Support Vector Machine

- Classifies crime levels using SVM classifier.
- **Accuracy:** 0.9915311653116531

### 5. Decision Tree

- Classifies crime levels using a decision tree classifier.
- **Accuracy:** 1.0

### 6. Random Forest

- Classifies crime levels using an ensemble of decision trees.
- **Accuracy:** 0.9979674796747967

### 7. Naive Bayes

- Classifies crime levels using Gaussian Naive Bayes.
- **Accuracy:** 0.9800135501355014

### 8. Clustering

- Performs clustering on crime data based on crime types.
- **Algorithms used:** K-Means, Hierarchical Clustering, DBSCAN.

