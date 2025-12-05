# 🧠 Assignment 18 — Neural Networks (ANN)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on implementing an **Artificial Neural Network (ANN)** using the **Sonar dataset**.  
Neural networks are powerful models capable of learning complex non-linear patterns, making them suitable for various classification tasks.

---

## 📘 Dataset: sonardataset.csv

The Sonar dataset contains **60 numerical features** representing sonar signal frequencies.  
Each instance is labeled as:

- **R** — Rock  
- **M** — Mine  

This dataset is commonly used to classify objects detected by sonar signals.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preparation
- Importing dataset using Pandas  
- Converting categorical labels (R/M) into numeric form  
- Splitting dataset into training and testing sets  
- Normalizing/standardizing the input features  

---

## 🧠 2. Building the Neural Network (ANN)

The notebook likely includes:

### **Model Architecture**
- Input layer (60 features)  
- Hidden layers with activation functions  
- Output layer for binary classification  

### **Training Process**
- Using TensorFlow/Keras  
- Selecting activation functions (ReLU, Sigmoid, etc.)  
- Loss function: Binary Crossentropy  
- Optimizer: Adam (commonly used)  
- Monitoring training accuracy & loss  

---

## 📉 3. Model Evaluation
- Accuracy score  
- Confusion matrix  
- ROC curve / AUC (if included)  
- Visualization of training curves  

### **Feature Scaling Impact**
Neural networks perform significantly better after feature normalization.

---

## 📊 4. Visualizations
- Loss vs epochs  
- Accuracy vs epochs  
- Prediction analysis  

---

## 📄 Files Included

- **Assignment18_[Neural_Networks].ipynb**  
  Google Colab notebook implementing the ANN model.

- **sonardataset.csv**  
  Dataset used for training and testing the neural network.

---

## ▶️ How to Run the Notebook

### **On Google Colab**
1. Upload `.ipynb` and the dataset to your Drive  
2. Open notebook using Google Colab  
3. Update dataset path if needed  
4. Train the ANN and evaluate results  

### **Run Locally (Optional)**

Install dependencies:

```bash
pip install numpy pandas tensorflow matplotlib seaborn scikit-learn notebook
