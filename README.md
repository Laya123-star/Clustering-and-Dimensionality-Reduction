# 🌸 Iris Dataset Clustering Analysis

An unsupervised machine learning project focused on applying and understanding clustering techniques using the classic Iris dataset.

---

## 📘 Project Overview

- This project implements **clustering algorithms** on the **Iris dataset** available from the `sklearn` library.
- Since clustering is an **unsupervised learning task**, the target labels (species) are intentionally excluded during model training.
- The objective is to group similar data points based on feature similarity and visualize the resulting clusters.

**🎯 Objective:**

The project includes:

🔹 Loading and preprocessing the dataset. 

🔹 Feature scaling for distance-based algorithms.

🔹 Implementation of KMeans clustering.

🔹 Implementation of Hierarchical clustering.

🔹 Cluster visualization and interpretation.

🔹 Clear explanations.

---

## 📂 Dataset Description

The **Iris dataset** consists of measurements of iris flowers belonging to three different species.

| Feature Name | Description |
|-------------|------------|
| Sepal Length | Length of the sepal (cm) |
| Sepal Width | Width of the sepal (cm) |
| Petal Length | Length of the petal (cm) |
| Petal Width | Width of the petal (cm) |

> Note: The **species column is dropped** during preprocessing since clustering.
> does not use class labels.

---

## 🧹 Preprocessing Steps

The following preprocessing steps were performed before applying clustering:

✔ **Dataset Loading:**  
The Iris dataset was loaded using `load_iris()` from the sklearn library.

✔ **DataFrame Conversion:**  
The feature data was converted into a Pandas DataFrame for easier analysis.

✔ **Data Quality Checks:**  
The dataset was checked for **missing values**, **duplicate records**, and **outliers** to ensure data consistency and reliability before clustering.

✔ **Label Removal:**  
The species column was excluded to ensure the task remains unsupervised.

✔ **Feature Scaling:**  
Standardization was applied using `StandardScaler` to ensure all features contribute equally to distance calculations.

---

## 📌 Clustering Algorithms Implemented

### 🔹 KMeans Clustering

- KMeans clustering partitions data into a predefined number of clusters by minimizing the distance between data points and their assigned cluster centroids.
- The **Elbow Method** was used to determine the optimal number of clusters.
- Based on the elbow plot, **k = 3** was selected as it provided a clear balance between compactness and simplicity.

**Visualization:**
- Scatter plots were used to visualize the clusters formed by KMeans.

---

### 🔹 Hierarchical Clustering

- Hierarchical clustering builds clusters step by step based on the distance between data points.
- Initially, each data point is treated as its own cluster, and the closest clusters are repeatedly merged.
- A **dendrogram** was used to visualize the hierarchical merging process.
- By cutting the dendrogram at an appropriate distance, three meaningful clusters were identified.

**Visualization:**
- Dendrogram for hierarchical structure.
- Scatter plot for final cluster representation.

---

## 📊 Visualizations Included

| Purpose | Visualization Type |
|------|-------------------|
| Optimal cluster selection | Elbow plot |
| KMeans cluster visualization | Scatter plot |
| Hierarchical structure | Dendrogram |
| Cluster comparison | Scatter plot |

All visualizations were chosen based on the nature of the data and clustering task.

---

## 🧠 Key Observations

- ✔ Feature scaling significantly improves clustering performance.
- ✔ KMeans efficiently grouped data into compact clusters.
- ✔ Hierarchical clustering provided a clear visual understanding of cluster formation.
- ✔ Both methods produced meaningful clusters on the Iris dataset.
- ✔ Dimensionality reduction helped improve visualization clarity.

---

## 🛠 Tech Stack

| Tool | Purpose |
|----|--------|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Scikit-learn | Clustering algorithms |
| Google Colab | Execution environment |

---

## 📁 Repository Structure

ML-Assignment-5-Clustering/

├── 📄 Clustering_and_Dimensionality_Reduction.ipynb  
├── 📄 README.md  

---

## 🚀 How to Run the Project

1. Open the notebook in **Google Colab**.
2. Run all cells sequentially from top to bottom.
3. The notebook will perform preprocessing, clustering, and visualization automatically.

---

## 📌 Submission Note

This repository is submitted as part of an academic assignment to demonstrate the application of **clustering techniques in unsupervised learning**.
All explanations and results are strictly based on the implemented code.
