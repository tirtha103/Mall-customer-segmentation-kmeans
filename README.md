# Mall Customer Segmentation using K-Means Clustering  
>  Submitted by: Tirtha Dutta  
>  Model Type: Clustering (Unsupervised Learning)

---

##  Objective  
Perform customer segmentation using **K-Means Clustering** on the Mall Customer Dataset to identify natural groups within the customer base for business insights.

---

##  Dataset  
- **Source:** [Kaggle – Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **Rows × Columns:** 200 × 5  
- **Features Used:**  
  - `Annual Income (k$)`  
  - `Spending Score (1–100)`  
- **Target:** *None* (Unsupervised Learning)

---

##  Workflow Summary  

### 1️ Data Cleaning & Preprocessing  *(Proof from Task 1)*  
- Checked for missing values →  None  
- Cleaned and saved to `data/mall_customers_cleaned.csv`  
- Verified data types and value ranges

### 2️ Exploratory Data Analysis *(Proof from Task 2)*  
- Boxplots and pairplots used to analyze distribution  
- Correlation heatmap generated and saved

### 3️ Feature Scaling *(Proof from Task 6)*  
- Standardized numeric features using `StandardScaler`

### 4️ K-Means Clustering (Main Task)  
- Applied **K-Means** for `K = 1` to `K = 10`  
- Optimal clusters determined using the **Elbow Method** → **K = 5**  
- Visualized clusters in 2D  
- Evaluated performance using **Silhouette Score**

---

##  Final Results  

| Metric                  | Value   |
|-------------------------|---------|
| Optimal Clusters (K)    | 5       |
| Silhouette Score        | 0.3576  |

---

##  Visual Proofs  

| Proof Type              | File Path                                |
|-------------------------|------------------------------------------|
| Elbow Method Plot       | `images/elbow_method.png`                |
| Cluster Visualization   | `images/cluster_plot.png`                |
| Silhouette Score Output | In notebook (`kmeans_clustering.ipynb`)  |

---

##  Tools & Libraries Used  
- Python 3.10+  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook

---

##  License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

