# 🍷 Assignment 14 — Principal Component Analysis (PCA)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on performing **Principal Component Analysis (PCA)** using the Wine dataset.  
PCA is a powerful dimensionality reduction technique used to simplify datasets by extracting the most important features while retaining most of the variance.

---

## 📘 Dataset: wine.csv

The Wine dataset is a classic multivariate dataset containing chemical properties of wine samples.

### **Features include:**
- Alcohol  
- Malic Acid  
- Ash  
- Alcalinity of Ash  
- Magnesium  
- Total Phenols  
- Flavanoids  
- Nonflavanoid Phenols  
- Proanthocyanins  
- Color Intensity  
- Hue  
- OD280/OD315 of diluted wines  
- Proline  

### **Target Variable:**
- Wine Class (1, 2, or 3)

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preprocessing
- Reading the dataset using Pandas  
- Checking for missing values  
- Standardizing the data (important for PCA)  
- Splitting features and target  

---

## 🧠 2. Applying PCA

The notebook covers:

- Computing covariance matrix  
- Extracting eigenvalues and eigenvectors  
- Computing principal components  
- Reducing dimensions (e.g., from 13 to 2 or 3 components)  
- Plotting explained variance ratio  

### 🔸 Visualizations include:
- Scree plot  
- 2D PCA scatter plot  
- PCA component contribution  

---

## 📉 3. Insights & Interpretation

Through PCA, you will learn:

- Which features contribute the most to variance  
- How dimensionality reduction helps improve ML efficiency  
- How PCA transforms data into orthogonal components  
- How class separation appears in PCA feature space  

---

## 📄 Files Included

- **Assignment14_[PCA].ipynb**  
  Notebook demonstrating PCA step-by-step, including visualizations.

- **wine.csv**  
  Dataset used for dimensionality reduction and visualization.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload `.ipynb` and dataset to Google Drive  
2. Open the notebook with Google Colab  
3. Ensure correct file paths  
4. Run all cells  

### **Run Locally (Optional)**

Install necessary libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
