# Fruits-360 with Dim Reduction to 188 dims
---
This repository  demonstrates the effective use of machine learning algorithms for handling high-dimensional image data from the Fruits-360 dataset. Specifically, Principal Component Analysis is employed to reduce the data from **30,000 dimensions (100x100x3) to just 188 dimensions**, while **preserving 95% of the original information**.

![](/assets/Imagen3.png)

This reduction significantly improves the efficiency and performance of the models.

## **Flow**
- Exploratory Data Analysis
- Anomaly Detection
- Pre-process
- Dimensionality Reduction 
- Classification
  - KNN
  - SVM
  - MLP
- Ensemble Classification
  - Hard Voting
  - Soft Voting  

## **Visualization**
![](/assets/pca_tsne.png)

## **Anomaly detection using Isolation Forest**
![](/assets/outlier1.jpg)

## **Results**
| Modelo | Tipo de clasificación | Accuracy |
| -------|-----------------------|----------|
| Hard voting  | Hard voting | 90.30% |
| Soft Voting | | Soft Voting | 89.94% |
| Support Vector Machin | Probabilística | 89.95% |
|K-Nearest Neighbors| Probabilística | 88.39% |
|Multi-layer Perceptron | Probabilística | 86.19% |
