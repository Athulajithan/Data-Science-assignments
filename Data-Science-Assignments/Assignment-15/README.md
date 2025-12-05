# ✈️ Assignment 15 — Clustering (K-Means & Hierarchical)  
**Author:** Athul N A  
**Platform:** Google Colab  

This assignment applies **unsupervised learning techniques**, specifically **K-Means** and **Hierarchical Clustering**, to the *EastWestAirlines* dataset.  
The goal is to group airline passengers based on their travel behavior and loyalty metrics, enabling insights useful for customer segmentation.

---

## 📘 Dataset: EastWestAirlines.xlsx

This dataset contains customer information from an airline company.  
Typical features include:

- Balance  
- Qualmiles  
- Bonusmiles  
- Bonus transactions  
- Flight miles  
- Days since enrollment  
- Various loyalty metrics  

These variables help identify different clusters of airline customers such as frequent flyers, loyal members, or occasional travelers.

---

## 🔎 Tasks Performed

### 🔹 1. Data Loading & Preprocessing
- Importing `.xlsx` file using Pandas  
- Handling missing values  
- Feature scaling using StandardScaler  
- Selecting relevant features for clustering  

---

## 🧠 2. K-Means Clustering
- Choosing the number of clusters using:
  - Elbow Method  
  - Silhouette Score  
- Training the K-Means model  
- Assigning cluster labels  
- Visualizing results with scatterplots  

---

## 🌳 3. Hierarchical Clustering
- Creating dendrograms using Ward linkage  
- Determining optimal cluster count  
- Applying Agglomerative Clustering  
- Comparing results with K-Means  

---

## 📊 4. Visualizations
- Dendrograms  
- Cluster scatter plots  
- Heatmaps  
- Line and distribution plots for cluster profiles  

---

## 🧩 5. Cluster Profiling

For each cluster, the notebook analyzes:

- Customer purchasing behavior  
- Loyalty characteristics  
- Travel habits  
- Key differentiating features  

This helps understand the type of customers in each group (e.g., high-value frequent flyers, occasional travelers, etc.).

---

## 📄 Files Included

- **Assignment15_[Clustering].ipynb**  
  Notebook containing k-means and hierarchical clustering implementations.

- **EastWestAirlines.xlsx**  
  Dataset used for clustering and customer segmentation.

---

## ▶️ How to Run the Notebook

### **Open in Google Colab**
1. Upload both files to Google Drive  
2. Open notebook → Google Colab  
3. Update dataset path if needed  
4. Run all cells  

### **Run Locally (Optional)**

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy openpyxl notebook
