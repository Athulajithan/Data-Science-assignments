# 🚗 Assignment 7 — Multiple Linear Regression (MLR)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on building a **Multiple Linear Regression (MLR)** model using the **Toyota Corolla dataset**, which contains car pricing and related features.  
The goal is to understand how multiple variables together influence the target variable — car price — and evaluate the model’s effectiveness.

---

## 📘 Dataset: ToyotaCorolla - MLR.csv

This dataset includes key attributes such as:

- Age of the car  
- Kilometers driven  
- Fuel type  
- HP (Horsepower)  
- Engine size  
- Number of doors  
- Weight  
- Price (target variable)

These features help in predicting the resale value of a car.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Cleaning
- Reading dataset with Pandas  
- Removing null values  
- Handling categorical variables (if needed)  
- Selecting relevant features  

### 🔹 2. Exploratory Data Analysis (EDA)
- Summary statistics  
- Correlation matrix  
- Scatter plots & distribution plots  
- Multicollinearity detection using heatmaps  

### 🔹 3. Building the MLR Model
- Splitting data into train/test sets  
- Fitting a regression model  
- Understanding coefficients  
- Interpreting p-values & significance of features  

### 🔹 4. Model Evaluation
- R² score  
- Adjusted R²  
- RMSE  
- Residual analysis  
- Checking model assumptions (normality, homoscedasticity, independence)  

### 🔹 5. Improving the Model
- Removing insignificant variables  
- Feature engineering  
- Transformations (if applied)  

---

## 📄 Files Included

- **assignment-7(MLR).ipynb**  
  A complete Google Colab notebook demonstrating MLR from start to finish.

- **ToyotaCorolla - MLR.csv**  
  Dataset used for training and testing the regression model.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload both the notebook and dataset to Google Drive  
2. Right-click → **Open with → Google Colab**  
3. Ensure dataset path is correct  
4. Run all cells

### **Run Locally (Optional)**

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
jupyter notebook
