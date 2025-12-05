# 🩺 Assignment 8 — Logistic Regression  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on building a **Logistic Regression** model using the popular **Diabetes dataset**.  
The goal is to classify whether a patient is diabetic or not based on medical attributes.  
Additionally, this assignment includes a **model deployment script** showcasing how to serve the trained model using Streamlit.

---

## 📘 Dataset: diabetes.csv

The dataset contains medical diagnostic features such as:

- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

The target variable indicates whether the person is **Diabetic (1)** or **Not Diabetic (0)**.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Cleaning
- Importing the dataset using Pandas  
- Handling missing values  
- Statistical summary and basic EDA  

### 🔹 2. Feature Engineering
- Selecting relevant features  
- Scaling (if applied)  
- Handling outliers  

### 🔹 3. Training Logistic Regression Model
- Splitting data into Train & Test sets  
- Training the classification model  
- Understanding model coefficients  
- Evaluating model performance  

### 🔹 4. Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- Precision, Recall, F1-score  
- ROC curve & AUC  

### 🔹 5. Model Deployment (Streamlit)
The assignment includes a **Streamlit deployment script** (`Model_Dep.py`) that:

- Loads a trained logistic regression model  
- Accepts user inputs (Pregnancies, Glucose, BMI, etc.)  
- Predicts whether the user is diabetic or not  
- Displays prediction probability  

Here is the deployment script used in this assignment:  
📄 **Model_Dep.py** :contentReference[oaicite:0]{index=0}

---

## 📄 Files Included

- **Assignment8(Logistic_Regression).ipynb**  
  Main notebook containing logistic regression analysis.  

- **diabetes.csv**  
  Dataset used for training and model evaluation.  

- **Model_Dep.py**  
  Streamlit deployment script for serving the trained model.  

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload `.ipynb` and `diabetes.csv` to Google Drive  
2. Right-click notebook → **Open with → Google Colab**  
3. Ensure file paths match  
4. Run all cells  

### **Run Locally (Optional)**

Install needed libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn streamlit
