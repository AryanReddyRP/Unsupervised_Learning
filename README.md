# 📊 Unsupervised Learning: K-Means Clustering on Cricket & Iris Datasets

A machine learning project demonstrating **unsupervised learning** using the **K-Means Clustering** algorithm. The project applies clustering techniques to the **Cricket** and **Iris** datasets, evaluates cluster quality using the Elbow Method and Silhouette Score, and visualizes the resulting clusters.

---

## 📌 Project Overview

This project explores how K-Means clustering can group similar data points without using target labels. It covers the complete clustering workflow, including data preprocessing, feature scaling, optimal cluster selection, model training, and visualization.

---

## 🚀 Features

- K-Means Clustering implementation
- Data preprocessing and feature scaling
- Elbow Method for optimal cluster selection
- Silhouette Score evaluation
- Cluster visualization
- Comparative analysis using multiple datasets
- Interpretation of clustering results

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Datasets

### Cricket Dataset
- Player statistics used for clustering based on performance metrics.

### Iris Dataset
- Classic machine learning dataset containing measurements of three Iris flower species.

---

## 🔄 Data Preprocessing

The preprocessing pipeline includes:

- Loading datasets
- Handling missing values (if applicable)
- Feature selection
- Feature scaling using **StandardScaler**
- Preparing data for clustering

---

## 🧠 Clustering Techniques

### K-Means Clustering

- Partition-based clustering algorithm
- Groups similar observations into **K clusters**
- Minimizes within-cluster variance (WCSS)
- Uses centroid-based optimization

### Cluster Evaluation

- **Elbow Method** to determine the optimal number of clusters
- **Silhouette Score** to evaluate clustering quality

---

## 🔄 Workflow

1. Load the datasets.
2. Perform data preprocessing and scaling.
3. Apply the Elbow Method to identify the optimal number of clusters.
4. Evaluate different cluster sizes using the Silhouette Score.
5. Train the final K-Means clustering model.
6. Visualize the generated clusters.
7. Interpret clustering results.

---

## 📊 Results

The project demonstrates:

- Selection of the optimal number of clusters
- Cluster assignment for each observation
- Cluster visualization
- Performance evaluation using the Silhouette Score

---

## 📁 Repository Structure

```text
├── unsupervised_learning.ipynb
├── cricket.csv
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Place the `cricket.csv` dataset in the project directory.
4. Open the Jupyter Notebook.
5. Execute all cells sequentially.
6. Analyze the clustering results and visualizations.

---

## 📈 Future Improvements

- Compare K-Means with Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models.
- Apply PCA for cluster visualization in lower dimensions.
- Experiment with different distance metrics and initialization methods.
- Evaluate clustering performance on additional real-world datasets.

---

## 👨‍💻 Author

**Aryan Reddy**

If you found this project useful, consider giving the repository a ⭐.
