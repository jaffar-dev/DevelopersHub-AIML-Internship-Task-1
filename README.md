# AI/ML Engineering Internship - DevelopersHub Corporation

This repository contains my completed technical tasks for the AI/ML Engineering Internship at DevelopersHub Corporation. 

## 📂 Repository Structure
* **Task1_Iris/**: Exploratory Data Analysis (EDA) and visualization using the classic Iris dataset.

---

## 🌸 Task 1: Exploring and Visualizing a Simple Dataset

### 🎯 Objective
To load, inspect, and visualize a dataset to uncover distributions, relationships, and hidden patterns across features before moving into machine learning modeling.

### 📊 Dataset Used
* **Iris Dataset**: Loaded natively via `seaborn`. It contains 150 instances of iris flowers spanning 3 unique species (*setosa*, *versicolor*, *virginica*), measured by 4 physical attributes (sepal length, sepal width, petal length, petal width).

### 🛠️ Libraries Applied
* **Pandas**: Structural data loading, inspection (`.info()`, `.describe()`), and table manipulation.
* **NumPy**: Underlying high-performance mathematical array management.
* **Matplotlib & Seaborn**: Statistical visualizations including scatter plots, histograms with kernel density lines, and box plots.

### 📈 Key Results & Findings
1. **Isolated Clusters**: Petal length and petal width display distinct, sharp classification boundaries per species, indicating that these features possess high predictive power for classification algorithms.
2. **Normal Distributions**: Sepal width aligns cleanly with a standard Gaussian (bell-curve) distribution.
3. **Data Health**: The box plots highlight minimal outliers across features, verifying that the dataset is highly clean and model-ready.