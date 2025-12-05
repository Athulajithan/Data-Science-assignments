# 🎭 Assignment 16 — Recommendation System  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment focuses on building a **Recommendation System** using the Anime dataset.  
Recommendation systems are widely used in platforms like Netflix, YouTube, and Amazon to suggest items based on user preferences and similarities.

---

## 📘 Dataset: anime.csv

The dataset includes thousands of anime titles with attributes such as:

- Anime name  
- Genre  
- Type (TV, Movie, OVA, etc.)  
- Episodes  
- Rating  
- Members count (popularity measure)  

This dataset is commonly used for learning collaborative filtering and content-based recommendation techniques.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Exploration
- Importing dataset with Pandas  
- Checking shape, null values, and data types  
- Cleaning dataset by removing or imputing missing values  
- Basic statistics and insights  

---

## 🎯 2. Building Recommendation Models

The notebook may implement one or more of the following:

### **Content-Based Filtering**
- Uses anime features (genre, type, rating)  
- Computes similarity between items using:
  - TF–IDF Vectorization  
  - Cosine Similarity  

### **Collaborative Filtering** *(if included)*  
- User-based or item-based similarity  
- Matrix-based recommendations  

### **Hybrid Approach** *(optional)*  
Combines content-based and collaborative signals.

---

## 📊 3. Visualizations & Insights
- Most popular anime  
- Genre frequency  
- Rating distributions  
- Similarity heatmaps  

---

## 🧪 4. Generating Recommendations

Example outputs include:

- **Top 10 similar anime** to a given title  
- Recommendations based on genre preference  
- Popular shows based on member count  

---

## 📄 Files Included

- **Assignment16_[Recommendation_System].ipynb**  
  Google Colab notebook implementing the recommendation system.

- **anime.csv**  
  Dataset used for similarity calculations and recommendations.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload the `.ipynb` and dataset to Google Drive  
2. Open the notebook in Colab  
3. Make sure file paths are updated  
4. Run all cells  

### **Run Locally (Optional)**

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
