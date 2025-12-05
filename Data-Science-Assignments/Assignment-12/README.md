# 🌲 Assignment 12 — Random Forest Classification  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on building a **Random Forest Classifier** using the **Glass Identification dataset**.  
Random Forest is an ensemble technique that combines multiple decision trees to improve classification accuracy and reduce overfitting.

---

## 🔍 Dataset: glass.xlsx

The dataset contains various chemical and optical properties of glass samples.  
These are used to classify glass into different categories based on their composition.

### **Features include:**
- Refractive index (RI)  
- Sodium (Na)  
- Magnesium (Mg)  
- Aluminum (Al)  
- Silicon (Si)  
- Potassium (K)  
- Calcium (Ca)  
- Barium (Ba)  
- Iron (Fe)  

### **Target Variable:**
- Glass Type (categorical classes such as building windows, vehicle windows, containers, etc.)

This dataset is widely used in classification research.

---

## 🧠 Tasks Performed

### 🔹 1. Data Loading & Preparation
- Importing XLSX file with Pandas  
- Checking dataset shape and structure  
- Cleaning missing or inconsistent values  
- Feature scaling (if needed)  
- Splitting data into training and testing sets  

### 🔹 2. Exploratory Data Analysis (EDA)
- Summary statistics  
- Pairplots / correlation heatmaps  
- Understanding chemical feature patterns  
- Class distribution analysis  

### 🔹 3. Building the Random Forest Model
- Using `RandomForestClassifier` from scikit-learn  
- Training the model on glass classification  
- Understanding ensemble behavior (bagging, bootstrapping)  

### 🔹 4. Model Evaluation
- Accuracy score  
- Confusion matrix  
- Classification report  
- Feature importance ranking  
- Comparing performance with Decision Tree  

### 🔹 5. Hyperparameter Tuning (Optional)
- n_estimators  
- max_depth  
- min_samples_split  
- bootstrap variations  

---

## 📄 Files Included

- **Assignment12_[Random_Forest].ipynb**  
  Google Colab notebook with complete Random Forest implementation.

- **glass.xlsx**  
  Glass identification dataset used for classification.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload the `.ipynb` and `glass.xlsx` files to Google Drive  
2. Right-click → **Open with Google Colab**  
3. Adjust dataset path if necessary  
4. Run all cells  

### **Run Locally (Optional)**

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl notebook
