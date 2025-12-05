# 📝 Assignment 19 — Natural Language Processing (NLP)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on **Natural Language Processing (NLP)** techniques applied to product reviews from Amazon.  
The core objective is to perform **Sentiment Analysis**, classifying reviews as positive or negative based on their text content.

---

## 📘 Dataset: amazonreviews.tsv

This dataset contains:

- Product review text  
- Sentiment label (Positive / Negative)  

The `.tsv` format means values are separated by tabs.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Cleaning
- Reading TSV file with Pandas  
- Handling missing values  
- Lowercasing, trimming, removing symbols  
- Stemming / Lemmatization (if applied)  
- Removing stopwords  

---

## 🧠 2. Feature Extraction Techniques

The notebook may include:

### **Bag of Words (BoW)**
- CountVectorizer  
- Sparse matrix creation  

### **TF–IDF Vectorization**
- Converting text to weighted numeric features  
- Reducing effect of frequent words  

### **Train–Test Split**
Preparing data for ML model training.

---

## 🤖 3. Training Machine Learning Models

Likely models used:

- Logistic Regression  
- Naive Bayes (MultinomialNB)  
- SVM (if included)  
- Other classifiers from scikit-learn  

Models are trained to classify sentiment from the review text.

---

## 📉 4. Evaluation Metrics
- Accuracy score  
- Confusion matrix  
- Classification report  
- ROC–AUC (if applicable)  

The goal is to compare models and pick the one that performs best.

---

## 📊 5. Visualizations & Insights
- Word frequency distributions  
- Word clouds (if generated)  
- Review length analysis  
- Distribution of positive vs negative reviews  

---

## 📄 Files Included

- **assignment19_[NLP].ipynb**  
  Complete notebook for NLP preprocessing, vectorization, training, and evaluation.

- **amazonreviews.tsv**  
  Dataset used for sentiment classification.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload `.ipynb` and `.tsv` file to Google Drive  
2. Open the notebook using Google Colab  
3. Update file paths if required  
4. Run all preprocessing + modeling steps  

### **Run Locally (Optional)**

Install libraries:

```bash
pip install numpy pandas scikit-learn nltk matplotlib seaborn notebook
