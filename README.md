** ## Customer Segmentation via Unsupervised Clustering Techniques**
---

### 📌 Project Overview

This project implements a robust machine learning pipeline to perform **customer segmentation** using unsupervised learning techniques. The objective is to identify meaningful customer groups within a retail dataset to enable targeted marketing, product personalization, and business intelligence strategies.

Through careful preprocessing, analysis, and model selection, this notebook demonstrates the power of **K-Means**, **Agglomerative Clustering**, and visualization techniques to understand customer behaviors based on age, income, and spending scores.

---

### 📂 Dataset Description

The dataset used in this project is titled `Customers.csv` and contains the following key features:

| Feature          | Description                                 |
| ---------------- | ------------------------------------------- |
| `CustomerID`     | Unique identifier assigned to each customer |
| `Gender`         | Categorical feature (Male / Female)         |
| `Age`            | Customer age in years                       |
| `Annual Income`  | Annual income in thousands of USD           |
| `Spending Score` | Score (1–100) assigned by the store         |

---

### 📈 Workflow Summary

#### 1. **Data Preprocessing**

* Inspection of missing/null values
* Data cleaning and encoding
* Feature scaling using StandardScaler

#### 2. **Exploratory Data Analysis (EDA)**

* Distribution plots for feature understanding
* Correlation heatmaps
* Cluster tendencies through pair plots

#### 3. **Clustering Techniques**

* ✅ K-Means Clustering with Elbow Method & Silhouette Analysis
* 🧬 Agglomerative (Hierarchical) Clustering with Dendrograms
* 🧪 (Optional) DBSCAN for density-based grouping

#### 4. **Model Evaluation**

* Optimal `k` selection using:

  * **Elbow Method**
  * **Silhouette Coefficient**
* Cluster visualization with color-coded scatter plots

---

### 📃 Key Findings & Insights

* The optimal number of clusters (`k`) was determined to be **5**, based on distortion and silhouette metrics.
* Clear customer segments were identified:

  * High Income – Low Spend
  * Low Income – High Spend
  * Young Spenders
  * Economical Elders
  * Average Consumers
* Hierarchical clustering validated the segmentation logic through **dendrogram branching**.

---

### 🚀 Running the Project

#### 🛠️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/customer-segmentation-clustering.git
   cd customer-segmentation-clustering
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Notebook**

   ```bash
   jupyter notebook Assignment6_Clustering.ipynb
   ```

#### 📦 Required Libraries

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* `scipy`

---

### 📈 Visual Output (Sample)

> *(Attach or embed clustering visualization outputs from the notebook here)*

---

### 📁 Repository Structure

```
📆 customer-segmentation-clustering/
│
├── 📄 Assignment6_Clustering.ipynb    # Main analysis notebook
├── 📈 Customers.csv                   # Dataset file
├── 📄 README.md                       # Project documentation
└── 📆 requirements.txt                # Python dependencies
```

---

### 🏁 Conclusion

This project demonstrates how unsupervised learning techniques can effectively cluster customers into meaningful groups without labeled data. The insights gained can be readily utilized to drive personalized business strategies and increase customer retention.

---

### 🤝 Author & Acknowledgments

**Developed by:** *Tanveer Singh*
🎓 *B.Tech CSE, Thapar Institute of Engineering & Technology*
🔗 [LinkedIn Profile](https://www.linkedin.com/in/tanveer-singh-bedi-a8b811177)
