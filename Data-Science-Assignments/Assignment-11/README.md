# 🌳 Assignment 11 — Decision Tree Classification  
**Author:** Athul N A  
**Platform:** Google Colab  

In this assignment, a **Decision Tree Classifier** is built using the **Heart Disease dataset**.  
The goal is to understand how decision trees split data based on feature values to classify whether a patient is at risk of heart disease.

---

## ❤️ Dataset: heart_disease.csv

This dataset contains various medical features including:

- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol level  
- Fasting blood sugar  
- Resting ECG results  
- Maximum heart rate  
- Exercise-induced angina  
- ST depression & slope  
- Target (heart disease: 1 = Yes, 0 = No)

The decision tree model uses these features to predict the presence of heart disease.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preprocessing
- Loading the CSV dataset  
- Checking shape & basic structure  
- Handling missing or inconsistent values  
- Converting categorical variables into numeric format  
- Splitting features and target variables  

### 🔹 2. Exploratory Data Analysis (EDA)
- Summary statistics  
- Understanding distributions  
- Correlation heatmaps  
- Observing patterns related to heart disease  

### 🔹 3. Building the Decision Tree Model
- Using `DecisionTreeClassifier` from scikit-learn  
- Training the model on the dataset  
- Visualizing the structure of the tree  
- Understanding decision rules and splits  

### 🔹 4. Model Evaluation
- Accuracy score  
- Confusion matrix  
- Classification report  
- Overfitting check  
- Impact of hyperparameters such as:
  - max_depth  
  - min_samples_split  
  - criterion (gini/entropy)  

### 🔹 5. Tree Visualization
- Plotting the decision tree  
- Analyzing feature importance  

---

## 📄 Files Included

- **Assignment11[Decision_Tree].ipynb**  
  Complete Colab notebook with model training, visualization, and evaluation.

- **heart_disease.csv**  
  Dataset used for classification.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload notebook + dataset to Google Drive  
2. Open the notebook with Google Colab  
3. Adjust dataset path if needed  
4. Run all cells  

### **Run Locally (Optional)**

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn graphviz notebook
