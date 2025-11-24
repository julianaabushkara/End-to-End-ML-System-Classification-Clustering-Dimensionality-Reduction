# **Multi-Dataset Machine Learning Pipeline Framework**

This project implements a complete machine learning workflow applied to three distinct datasets: structured tabular data, image-based data, and high-dimensional synthetic data.
The goal is to explore how different modeling techniques behave under different data characteristics, and how preprocessing, dimensionality reduction, and feature selection influence performance, speed, and interpretability.

The project includes **classification**, **clustering**, **PCA**, **t-SNE visualization**, **feature engineering**, and **runtime analysis**, all implemented using Python and Scikit-learn.

---

## 🚀 **Features**

* Full ML workflow: preprocessing → modeling → evaluation
* Classification on tabular & image datasets
* Clustering with multiple algorithms
* PCA-based dimensionality reduction
* t-SNE visualization for non-linear structures
* Feature engineering and feature importance analysis
* Automatic feature selection pipeline
* Performance comparison before/after PCA and feature removal
* Runtime and efficiency benchmarking
* Clean, modular code structure

---

## 📚 **Datasets**

### **1. Forest Cover Dataset**

Structured tabular dataset for multi-class classification and clustering.

### **2. MNIST (Even Digits Only)**

Image dataset (0, 2, 4, 6, 8) used for classification and dimensionality reduction.

### **3. High-Dimensional Synthetic Data**

120-feature dataset used for:

* Feature importance analysis
* Correlation handling
* Outlier detection

---

## 🧩 **Project Components**

### **🔍 Data Exploration**

* Statistical summaries
* Distribution plots
* Heatmaps and correlation analysis
* Outlier detection

### **🧼 Preprocessing**

* Train/validation/test splits
* Imputation & scaling
* Feature engineering
* Dimensionality handling

### **🤖 Classification Models**

* Random Forest
* Support Vector Machines
* K-Nearest Neighbors
* Hyperparameter tuning
* Comparison across datasets
* Runtime tracking

### **🌀 Clustering**

* K-Means
* Hierarchical Clustering
* Evaluation using Silhouette / Davies-Bouldin
* Visualization before & after PCA

### **📉 Dimensionality Reduction**

* PCA (retain ≥80% variance)
* PCA projection visualizations
* Comparative performance analysis

### **🎨 t-SNE Visualization**

* 2D/3D embeddings
* Color-coded clusters
* Insights on structure separability

### **📊 Feature Selection**

* PCA loading analysis
* Identification of weak/strong features
* Automated feature removal based on variance contribution
* Re-training & performance comparison

### **🧪 Outlier Detection**

* PCA anomaly scoring
* Statistical thresholding
* Evaluation using precision/recall

---

## 📊 **Evaluation Metrics**

* Accuracy
* Macro F1-Score
* Confusion matrices
* Training/prediction runtime
* Silhouette Index
* Davies-Bouldin Index
* PCA explained variance ratios



## 🧠 **Technologies**

* Python
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn
* PCA & t-SNE
* Jupyter Notebook

---

## ✨ **Project Goals**

* Build a unified ML experimentation platform
* Compare model behavior across dataset types
* Understand how dimensionality reduction affects performance
* Explore real-world and synthetic high-dimensional patterns
* Create reproducible pipelines for ML research



Just tell me!
