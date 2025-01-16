# Iris Dataset Classification Project

## Overview
This project classifies the Iris dataset using three machine learning models:
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree

The goal is to evaluate and compare the performance of these models using metrics like accuracy, classification reports, and confusion matrices.

---

## Dataset
The Iris dataset consists of:
- **150 samples** from three classes:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Target**: Class labels (0, 1, 2)

---

## Steps

### 1. Load the Dataset
The dataset is loaded using `sklearn.datasets`.

### 2. Split the Dataset
Data is split into:
- 80% for training
- 20% for testing

### 3. Standardize Features
`StandardScaler` is used to scale the features for models like SVM and KNN.

### 4. Train Models
The following models are trained:
- SVM with a linear kernel
- KNN with `n_neighbors=5`
- Decision Tree

### 5. Evaluate Models
Metrics used:
- **Accuracy Score**: To measure overall performance.
- **Classification Report**: Provides precision, recall, and F1-score.
- **Confusion Matrix**: Visualized using heatmaps.

---

## Results

### Accuracy
- **SVM Accuracy**: ~ `<value>`%
- **KNN Accuracy**: ~ `<value>`%
- **Decision Tree Accuracy**: ~ `<value>`%

### Classification Reports
Detailed classification reports are generated for each model.

### Confusion Matrices
Heatmaps of confusion matrices are generated to show true vs. predicted labels for each model.

---

## How to Run

1. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
