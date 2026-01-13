 🛍️ Mall Customer Segmentation

## Overview
Segment mall customers using **K-Means Clustering** to understand spending behavior and target audiences.

---

## Features Used
- Age  
- Annual Income (k$)  
- Spending Score (1–100)

---

## Steps
1. Load and explore dataset  
2. Select features and determine optimal clusters (Elbow Method)  
3. Train **K-Means** model  
4. Evaluate using **Silhouette Score**  
5. Save model with **Joblib**  
6. Predict new customer cluster

---

## Cluster Interpretation

| Cluster | Customer Type |
|---------|---------------|
| 0 | Low Income – Low Spending |
| 1 | High Income – High Spending |
| 2 | Average Income – Average Spending |
| 3 | High Income – Low Spending |
| 4 | Low Income – High Spending |

## Tools Used
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Joblib
