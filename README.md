# Machine_Learning_Lab_Exercises
This repository contains Python implementations for three machine learning labs: visual EDA on the Iris dataset , image segmentation using K-Means clustering , and a comparison of PCA and Kernel PCA for dimensionality reduction

---

## Table of Contents
- [Lab 2: Visual Exploratory Data Analysis](#-lab-2-visual-exploratory-data-analysis)
- [Lab 3: K-Means Clustering for Image Segmentation](#-lab-3-k-means-clustering-for-image-segmentation)
- [Lab 4: Principal Component Analysis (PCA)](#-lab-4-principal-component-analysis-pca)

---

## 📊 Lab 2: Visual Exploratory Data Analysis
<a name="-lab-2-visual-exploratory-data-analysis"></a>

### Description
[cite_start]The objective of this lab was to perform visual exploratory data analysis (EDA) to understand class separability and feature importance[cite: 227]. [cite_start]The analysis was conducted on the Iris dataset [cite: 239][cite_start], utilizing various visualization techniques to identify the most discriminative features[cite: 460].

### Key Techniques
- [cite_start]**Pair Plots**: To show pairwise relationships between features and identify class clusters[cite: 234].
- [cite_start]**Box Plots & Violin Plots**: To display data distribution, spread (IQR), and outliers for each feature across different species[cite: 235, 236].
- [cite_start]**Correlation Heatmap**: To summarize the linear relationships between features[cite: 237].

### Files
- `Lab2_EDA/lab2_eda.py`: The Python script used to generate the plots and perform the analysis.
- `Lab2_EDA/2025124988_ML_Lab_02_Submission.pdf`: The detailed lab report with annotated visualizations and conclusions.

---

## 🎨 Lab 3: K-Means Clustering for Image Segmentation
<a name="-lab-3-k-means-clustering-for-image-segmentation"></a>

### Description
[cite_start]This lab demonstrates the implementation of K-Means clustering and its application in image segmentation[cite: 515]. [cite_start]The algorithm groups pixel colors into a predefined number of clusters (K) to simplify the image into its dominant colors[cite: 519].

### Key Techniques
- [cite_start]**K-Means Clustering**: Applied to the RGB values of image pixels to segment the image into K color regions[cite: 542, 555].
- [cite_start]**Elbow Method**: Used to determine the optimal number of clusters (K) by plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters and finding the "elbow" point[cite: 563, 583].

### Files
- `Lab3_Clustering/lab3_clustering.py`: The Python script for loading an image, applying K-Means, and generating segmented results.
- `Lab3_Clustering/Exercise3_Clustering_2025124988.pdf`: The lab report showing the segmented images for different K values and the analysis using the elbow method.

---

## 📉 Lab 4: Principal Component Analysis (PCA)
<a name="-lab-4-principal-component-analysis-pca"></a>

### Description
[cite_start]The objective of this exercise was to implement and demonstrate Principal Component Analysis (PCA) and Kernel PCA (KPCA)[cite: 3]. [cite_start]PCA is a linear technique used to project data onto directions of maximum variance [cite: 5][cite_start], while KPCA extends this to capture non-linear relationships[cite: 6]. [cite_start]The lab compares their effectiveness on synthetic non-linear datasets and their impact on classifier performance[cite: 3, 63].

### Key Techniques
- **Principal Component Analysis (PCA)**: Implemented to reduce dimensionality. [cite_start]Steps include standardizing data, computing the covariance matrix, and performing eigen decomposition[cite: 9, 10, 11].
- [cite_start]**Kernel PCA (KPCA)**: Used to handle non-linear data by using a kernel function (like RBF) to project data into a higher-dimensional space before applying PCA[cite: 6, 35].
- [cite_start]**Classifier Performance Comparison**: A logistic regression classifier was used to compare the accuracy of a model trained on original features versus features reduced by PCA and KPCA[cite: 63, 214].

### Files
- `Lab4_PCA/lab4_pca.py`: The Python script demonstrating the implementation of PCA and KPCA on the "two moons" and ISOLET datasets.
- `Lab4_PCA/2025124988_Lab_Exercise_4_PCA_submission.pdf`: The detailed lab report containing code, outputs, and inferences on reconstruction error and classifier performance.
