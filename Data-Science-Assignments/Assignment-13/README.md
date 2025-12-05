# ⚡ Assignment 13 — LightGBM & XGBoost Classification  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on implementing two powerful gradient boosting algorithms — **LightGBM (LGBM)** and **XGBoost (XGB)** — using the Diabetes dataset.  
These algorithms are widely used in competitive machine learning and real-world applications due to their high accuracy, speed, and performance with structured data.

---

## 📘 Dataset: diabetes.csv

The dataset includes medical diagnostic features such as:

- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

The target variable indicates whether the person is **Diabetic (1)** or **Not Diabetic (0)**.

This dataset is commonly used for classification tasks.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preprocessing
- Reading dataset using Pandas  
- Handling missing values  
- Scaling / Standardization (if applied)  
- Splitting into train & test sets  

### 🔹 2. Exploratory Data Analysis (EDA)
- Basic statistical exploration  
- Correlation heatmap  
- Feature importance analysis  

---

## ⚡ 3. Training Gradient Boosting Models

### **🔸 LightGBM (LGBMClassifier)**
- Faster training compared to XGBoost  
- Leaf-wise growth strategy  
- Handles large feature sets efficiently  

### **🔸 XGBoost (XGBClassifier)**
- Gradient boosting with regularization  
- Highly effective for tabular data  
- Commonly used in Kaggle competitions  

---

## 🔥 4. Model Evaluation

Both models were evaluated using:

- Accuracy score  
- Confusion matrix  
- Classification report  
- ROC–AUC score  
- Feature importance plots  

Additionally:

- Hyperparameter tuning may have been performed  
- Comparison between LGBM and XGB performance  

---

## 📄 Files Included

- **Assignment13_[LGBM&XGBM].ipynb**  
  Colab notebook with complete LGBM and XGB implementation, comparison, and evaluation.

- **diabetes.csv**  
  Dataset used for model training and testing.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload the `.ipynb` and dataset to Google Drive  
2. Open the notebook in Google Colab  
3. Adjust dataset path if needed  
4. Run cells to reproduce results  

### **Run Locally (Optional)**

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm notebook
