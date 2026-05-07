# Principal Component Analysis (PCA) 

This project demonstrates the implementation of **Principal Component Analysis (PCA)** on the famous Iris dataset using Python and Scikit-learn.

PCA is used for:
- Dimensionality Reduction
- Feature Extraction
- Variance Analysis
- Data Visualization

The project analyzes how much variance is captured by each principal component and visualizes the results using Scree Plots and Bar Charts.

---

## 📌 Project Objective

The main objective of this project is to:
- Reduce the dimensionality of the dataset
- Identify the most important features
- Analyze explained variance
- Understand PCA component loadings

---

## 📊 Dataset

Dataset used: **Iris Dataset**

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:
- Setosa
- Versicolor
- Virginica

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Project Workflow

1. Load the Iris dataset
2. Create a DataFrame
3. Standardize the features using StandardScaler
4. Apply PCA
5. Compute explained variance
6. Generate Scree Plot and Bar Plot
7. Analyze PCA loadings

---

## 📈 Visualizations

### Scree Plot
Shows the proportion of explained variance captured by each principal component.

### Bar Plot
Visual representation of explained variance ratios.

### PCA Loadings
Displays feature contributions to each principal component.

---

## 🚀 Results

- PC1 explains approximately **72%** of the variance.
- PC1 and PC2 together explain approximately **96%** of the total variance.
- PCA successfully reduced the dimensional complexity while preserving most of the information.


```bash
git clone <your-repository-link>
