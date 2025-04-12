# Employee Retention Prediction using Machine Learning

# 🧠 Marketing Customer Segmentation & Clustering with K-Means & PCA

📌 Project Overview

This project analyzes employee attrition, job satisfaction, and performance trends using data science techniques. It provides insights into employee retention and helps HR departments make data-driven decisions.
This project applies **unsupervised machine learning** techniques to segment customers using **K-Means Clustering** and **Principal Component Analysis (PCA)**. The aim is to discover patterns in customer data to support targeted marketing strategies and customer behavior insights.

## 📊 Overview

- 📁 **Dataset:** Synthetic customer dataset including features like `BALANCE`, `PURCHASES`, `ONEOFF_PURCHASES`, `CASH_ADVANCE`, and more.
- 📌 **Goal:** Cluster customers into meaningful groups based on purchasing and credit behavior.
- 🚀 **Tools Used:** `Pandas`, `Matplotlib`, `Seaborn`, `Scikit-learn`, `PCA`, `KMeans`, `StandardScaler`

## 🧩 Key Steps

1. **Data Cleaning**
   - Handled missing values.
   - Removed irrelevant features.

2. **Feature Scaling**
   - Used `StandardScaler` to normalize features.

3. **Clustering**
   - Applied `KMeans` clustering with optimal number of clusters.
   - Evaluated using Elbow Method and silhouette score.

4. **Dimensionality Reduction**
   - Reduced features to 2D using PCA for visualization.

5. **Visualization**
   - Plotted PCA scatterplot with clusters colored.
   - Interpreted results for business insights.

---

## 📈 Result: 7 Clusters Found

Using PCA and clustering, the customers were grouped into **7 distinct segments** based on purchasing behavior. Each cluster represents different customer personas which could be:

- Low balance, low purchase
- High cash advance users
- High spenders, low cash users
- Regular customers with balance rollover
- And more...

These segments can guide marketing, credit strategies, and customer retention planning.

---

## 📦 Requirements

```bash
pip install pandas matplotlib seaborn scikit-learn
