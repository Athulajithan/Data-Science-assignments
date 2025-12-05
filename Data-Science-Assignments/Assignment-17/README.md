# 📈 Assignment 17 — Time Series Forecasting  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on **Time Series Analysis and Forecasting** using historical exchange rate data.  
Time series forecasting is essential in finance, economics, and trend prediction across multiple industries.  
The notebook explores the structure of time-series data and applies forecasting models to predict future exchange rates.

---

## 📘 Dataset: exchange_rate.csv

This dataset contains historical exchange rate values over time.  
Typical columns include:

- **Date**  
- **Exchange Rate (e.g., USD to AUD)**  

The data is used to analyze patterns, detect trends, and build forecasting models.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preparation
- Parsing date column  
- Converting data into time-series format  
- Handling missing values  
- Resampling (if applied)  

---

## 📉 2. Exploratory Time Series Analysis
- Line plot of exchange rate over time  
- Rolling mean & rolling standard deviation  
- Checking for stationarity  
- ADF (Augmented Dickey-Fuller) test  
- Trend, seasonality, and noise decomposition  

---

## 🤖 3. Time Series Modeling

The notebook may include:

### **🔸 ARIMA Model**
- ACF & PACF analysis  
- Parameter selection (p, d, q)  
- Model fitting  
- Forecast generation  

### **🔸 Exponential Smoothing**
- Simple Exponential Smoothing  
- Holt’s Linear Trend method  
- Holt-Winters method  
- Multi-step forecasting  

---

## 🧪 4. Forecast Evaluation
- RMSE  
- MAPE  
- Comparing ARIMA vs Exponential Smoothing results  
- Visual comparison of predicted vs actual values  

---

## 📊 5. Visualizations
- Time-series plot  
- Forecast vs actual graph  
- Model diagnostics plot  
- Seasonal decomposition plot  

---

## 📄 Files Included

- **Assignment17_[Timeseries].ipynb**  
  Complete time-series analysis and forecasting notebook.

- **exchange_rate.csv**  
  Dataset containing historical currency values.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload `.ipynb` and dataset to Google Drive  
2. Right-click → **Open with Colab**  
3. Adjust dataset path if needed  
4. Run all cells  

### **Run Locally (Optional)**

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn statsmodels scikit-learn notebook
