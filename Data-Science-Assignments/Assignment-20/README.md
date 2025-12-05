# 🔁 Assignment 20 — Recurrent Neural Networks (RNN)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on building a **Recurrent Neural Network (RNN)** model to forecast **monthly milk production**.  
RNNs are powerful for time-dependent data, especially when learning sequential patterns like trends and seasonality.

---

## 📘 Dataset: monthly_milk_production.csv

This dataset contains:

- Monthly milk production values  
- Timestamped data (Year–Month)  

It is a popular dataset for testing deep learning forecasting models.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preparation
- Reading time-series data  
- Parsing date column  
- Plotting historical milk production  
- Checking trends & seasonality  
- Normalizing the data  
- Creating sequences for RNN input  

---

## 🧠 2. Building the RNN Model

The notebook likely includes:

### **RNN Architecture**
- Input sequence layer  
- Simple RNN or LSTM layers  
- Dense output layer  

### **Training Details**
- Loss function: Mean Squared Error (MSE)  
- Optimizer: Adam  
- Epochs, batch size tuning  
- Training vs validation curves  

---

## 📉 3. Forecasting & Evaluation
- Predicting future milk production  
- Plotting predicted vs actual values  
- Error metrics such as RMSE or MAE  
- Model performance interpretation  

---

## 📊 4. Visualizations
- Raw time series  
- Trend & seasonal decomposition  
- Training loss curve  
- Forecast output curve  

---

## 📄 Files Included

- **Assignment20_[RNN].ipynb**  
  Colab notebook implementing RNN-based forecasting.

- **monthly_milk_production.csv**  
  Dataset containing historical milk production values.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload both files to Google Drive  
2. Open the notebook with Google Colab  
3. Adjust file path if required  
4. Train the RNN model & visualize forecasts  

### **Run Locally (Optional)**

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn tensorflow scikit-learn notebook
