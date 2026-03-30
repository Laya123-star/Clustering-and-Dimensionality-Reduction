# 🌸 Iris Dataset Clustering Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Data Analysis](https://img.shields.io/badge/DataAnalysis-EDA-orange)
![Visualization](https://img.shields.io/badge/Visualization-Seaborn-green)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)

An unsupervised machine learning project focused on applying and understanding clustering techniques using the classic Iris dataset.

---

## 🚀 Run Notebook in Google Colab

Click below to open the notebook:

[Open In Colab](https://colab.research.google.com/drive/1--gIB5m5EJM6buqbgIo4LsfpblftsZX2)

---

## 📘 Project Overview

- This project implements **clustering algorithms** on the **Iris dataset** available from the `sklearn` library.
- Since clustering is an **unsupervised learning task**, the target labels (species) are intentionally excluded during model training.
- The objective is to group similar data points based on feature similarity and visualize the resulting clusters.

---

## 🎯 Objective

The project includes:

🔹 Loading and preprocessing the dataset  
🔹 Feature scaling for distance-based algorithms  
🔹 Implementation of KMeans clustering  
🔹 Implementation of Hierarchical clustering  
🔹 Cluster visualization and interpretation  
🔹 Clear explanations  

---

## 📂 Dataset Description

The **Iris dataset** consists of measurements of iris flowers belonging to three different species.

| Feature Name | Description |
|-------------|------------|
| Sepal Length | Length of the sepal (cm) |
| Sepal Width | Width of the sepal (cm) |
| Petal Length | Length of the petal (cm) |
| Petal Width | Width of the petal (cm) |

> Note: The **species column is dropped** during preprocessing since clustering does not use class labels.

---

## 🧹 Preprocessing Steps

✔ Dataset loaded using `load_iris()` from sklearn  
✔ Converted into Pandas DataFrame  
✔ Checked for missing values, duplicates, and outliers  
✔ Species column removed (unsupervised learning)  
✔ Feature scaling applied using `StandardScaler`  

---

## 📌 Clustering Algorithms Implemented

### 🔹 KMeans Clustering
- Centroid-based clustering  
- Elbow Method used  
- Optimal clusters: **k = 3**  

### 🔹 Hierarchical Clustering
- Agglomerative approach  
- Dendrogram visualization  
- Final clusters: **3**  

---

## 📊 Model Comparison

| Model         | Silhouette Score |
|--------------|------------------|
| K-Means      | 0.459948         |
| Hierarchical | 0.446689         |

🏆 **Best Model:** K-Means (Silhouette Score = 0.460)

---

## 📊 Visualizations Included

- Elbow Plot  
- KMeans Scatter Plot  
- Dendrogram  
- Cluster Scatter Comparison  

---

## 🧠 Key Observations

✔ Feature scaling improves clustering performance  
✔ KMeans creates compact clusters  
✔ Hierarchical clustering improves interpretability  
✔ Both methods produce meaningful clusters  
✔ Dimensionality reduction enhances visualization  

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|--------|
| Python | Programming |
| Pandas | Data handling |
| NumPy | Computation |
| Matplotlib | Visualization |
| Seaborn | Visualization |
| Scikit-learn | ML algorithms |
| Google Colab | Execution |

---

## 📁 Repository Structure

ML-Assignment-5-Clustering/  

│  

├── Clustering_and_Dimensionality_Reduction.ipynb 

└── README.md  

---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. View clustering outputs and visualizations  

---

## ⚠️ Limitations

- Small dataset (150 samples) 
- Limited feature complexity  
- Sensitive to scaling and distance metrics  
- No advanced clustering techniques used  
- Limited parameter tuning  

---

## 📌 Academic Submission

This project is part of a Machine Learning academic assignment demonstrating **unsupervised learning and clustering techniques**.

---

## 📌 Future Enhancements

- Implement DBSCAN and Gaussian Mixture Models
- 
- Apply PCA for dimensionality reduction
- 
- Perform hyperparameter tuning
- 
- Build a Streamlit dashboard
- 
- Test on larger datasets  

---

## 👤 Author

**Name:** Laya Mary Joy  

**Organization:** Entri Elevate

**Date:** January 27, 2026  

---

## ⭐ Acknowledgment

Thanks to **Entri Elevate** for guidance and support.  

---
