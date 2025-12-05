# 🔄 Assignment 9 — Data Transformation  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on **Data Transformation techniques**, a crucial part of preprocessing before applying any Machine Learning model.  
Using the **Adult Income dataset**, the notebook demonstrates how to clean, encode, scale, and structure data into a form suitable for analysis and modeling.

---

## 📘 Dataset: adult_with_headers.csv

The Adult dataset includes demographic and financial attributes such as:

- Age  
- Workclass  
- Education  
- Occupation  
- Marital status  
- Hours per week  
- Native country  
- Income category (<=50K or >50K)

This dataset is widely used for experimentation in ML classification tasks.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Inspection
- Reading dataset with headers  
- Checking shape, datatypes, and missing values  
- Identifying categorical vs. numerical variables  

### 🔹 2. Handling Missing Values
- Replacing missing entries  
- Removing unnecessary rows or columns  

### 🔹 3. Encoding Categorical Data
- Label Encoding  
- One-Hot Encoding  
- Mapping categorical variables to numerical format  

### 🔹 4. Scaling & Normalization
- Min-Max Scaling  
- Standardization  
- Normalization for ML algorithms  

### 🔹 5. Outlier Detection & Treatment
- Using IQR method  
- Identifying extreme values in numerical columns  

### 🔹 6. Feature Transformation Techniques
- Log transformation  
- Binning  
- Feature selection  
- Converting skewed distributions to normal form  

### 🔹 7. Preparing Data for ML Models
- Combining all transformations  
- Creating a clean, model-ready dataset  

---

## 📄 Files Included

- **Assignment9(Data_Transformation).ipynb**  
  Google Colab notebook demonstrating complete preprocessing and transformation operations.

- **adult_with_headers.csv**  
  Dataset used for transformation tasks.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload the `.ipynb` and dataset into Google Drive  
2. Right-click → **Open with → Google Colab**  
3. Update the dataset path if needed  
4. Run all cells  

### **Run Locally (Optional)**

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
