# Municipal Clustering and Anomaly Detection

Data science project using **K-Means**, **Hierarchical Clustering**, and **Isolation Forest** applied to municipal socioeconomic data from **Paraíba, Brazil**.

## Overview

This project was developed for the **Unsupervised Machine Learning** course at the Federal University of Paraíba (UFPB).

The objective is to explore unsupervised learning techniques to identify patterns, group municipalities with similar characteristics, and detect anomalous cases using socioeconomic indicators.

## Objectives

The project is divided into three main tasks:

### 1. Municipal Health Profiles with K-Means
- Data preprocessing and feature selection
- Feature scaling
- Optimal number of clusters (Elbow Method & Silhouette Score)
- K-Means clustering
- Cluster interpretation
- Cluster stability analysis

### 2. Labor Market Profiles with Hierarchical Clustering
- Agglomerative Hierarchical Clustering
- Comparison of linkage methods (Ward, Complete, Average)
- Dendrogram analysis
- Cophenetic correlation coefficient
- Comparison with K-Means

### 3. Educational Anomaly Detection with Isolation Forest
- Isolation Forest model
- Different contamination values
- Anomaly score analysis
- PCA visualization
- Interpretation of detected anomalies

---

## Dataset

The dataset contains socioeconomic indicators for municipalities in the state of **Paraíba (Brazil)** for the year **2022**.

Each observation corresponds to a municipality–indicator pair and includes information related to:

- Health
- Labor market
- Education

The dataset is provided in **Parquet** format.

---

## Technologies

- Python 3
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```
.
├── data/
│   └── dados.parquet
│
├── notebooks/
│   └── clustering_anomaly_detection.ipynb
│
├── report/
│   └── report.pdf
│
├── figures/
│
├── requirements.txt
└── README.md
```

---

## Methods

### Clustering
- K-Means
- Agglomerative Hierarchical Clustering

### Cluster Evaluation
- Elbow Method
- Silhouette Score
- Cophenetic Correlation Coefficient

### Anomaly Detection
- Isolation Forest
- Principal Component Analysis (PCA)

---

## Results

The project provides:

- Identification of municipal health profiles
- Labor market segmentation
- Detection of atypical municipalities in education
- PCA visualization of anomalies
- Interpretation of clusters and anomalies for public policy applications

---

## Author

**Your Name**

Federal University of Paraíba (UFPB)

Course: Unsupervised Machine Learning
