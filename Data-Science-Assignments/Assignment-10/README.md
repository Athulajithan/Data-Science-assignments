# 🧪 Assignment 10 — Support Vector Machine (SVM)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment demonstrates how to apply the **Support Vector Machine (SVM)** algorithm to a real-world dataset from the pharmaceutical industry.  
The SVM model is used to classify and understand patterns in the dataset through various kernel functions and evaluation techniques.

---

## 📘 Dataset: Pharma_Industry.csv

This dataset contains pharmaceutical industry data with features such as:

- Company characteristics  
- Production or sales-related metrics  
- Class / Label for prediction  

The exact target variable depends on the structure of the dataset, but the notebook uses it for **classification tasks**.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preprocessing
- Import dataset using Pandas  
- Identify missing values  
- Clean and prepare data  
- Encode categorical variables (if present)  
- Feature scaling (important for SVMs)

### 🔹 2. Exploratory Data Analysis (EDA)
- Statistical summary  
- Visualizing feature distributions  
- Correlation analysis  
- Identifying patterns in industry features  

### 🔹 3. Building SVM Models
The assignment explores multiple SVM kernels:

- **Linear SVM**  
- **Polynomial kernel SVM**  
- **RBF kernel SVM**  
- **Sigmoid kernel (optional)**  

### 🔹 4. Model Evaluation
- Train-test splitting  
- Confusion matrix  
- Classification report  
- Accuracy score  
- Hyperparameter tuning (C, gamma, kernel)

### 🔹 5. Model Comparison
Comparing performance of:

- Linear vs. Non-linear kernels  
- Effect of feature scaling  
- Best kernel for this dataset  

---

## 📄 Files Included

- **Assignment10_[SVM].ipynb**  
  Contains complete SVM implementation, EDA, and evaluation.

- **Pharma_Industry.csv**  
  Dataset used for classification and model training.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload notebook and dataset to Google Drive  
2. Right-click notebook → **Open with → Google Colab**  
3. Adjust dataset path if needed  
4. Run all cells in order  

### **Run Locally (Optional)**

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook

