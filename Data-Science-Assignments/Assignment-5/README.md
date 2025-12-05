# 📊 Assignment 5 — Exploratory Data Analysis (EDA)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on performing **Exploratory Data Analysis (EDA)** on the **Cardiotocographic dataset**, which contains fetal monitoring data collected during pregnancy.  
The goal is to explore, understand, and visualize the dataset to uncover patterns, distributions, correlations, and insights relevant for medical decision-making.

---

## 📘 Dataset: Cardiotocographic.csv

This dataset includes various fetal and uterine features such as:

- Baseline fetal heart rate  
- Contractions  
- Accelerations  
- Abnormal short-term variability  
- Long-term variability  
- Histogram-based measurements  
- Fetal state classification  

The dataset is commonly used for classification tasks in medical ML applications.

---

## 🔎 EDA Tasks Performed

### 🔹 1. Data Loading & Cleaning
- Checking dataset shape and basic details  
- Handling missing values  
- Fixing inconsistent data types  
- Renaming columns (if necessary)

### 🔹 2. Descriptive Statistics
- Summary statistics (mean, median, std, etc.)  
- Understanding the distribution of key variables  
- Identifying skewness and variance  

### 🔹 3. Data Visualization
Using **Matplotlib** and **Seaborn**:

- Histograms  
- Boxplots  
- Pairplots  
- Correlation heatmaps  
- Line & distribution plots  
- Outlier detection visuals  

### 🔹 4. Insights & Interpretation
- Identifying features that affect fetal well-being  
- Detecting abnormal patterns  
- Observing relationships between physiological variables  
- Understanding fetal state labels  

---

## 📄 Files Included

- **EDA_Assignment_5.ipynb**  
  Contains complete exploratory analysis, visualizations, and insights.

- **Cardiotocographic.csv**  
  Dataset used for analyzing fetal state patterns.

---

## ▶️ How to Run the Notebook

### **Option 1 — Open in Google Colab**
1. Upload `.ipynb` and `.csv` into Google Drive  
2. Open the notebook using Google Colab  
3. Ensure the dataset path matches notebook code  
4. Run all cells

### **Option 2 — Run Locally**
Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn notebook
jupyter notebook
