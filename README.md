# SmartCart Segmentation System 🛒

An Unsupervised Machine Learning Customer Segmentation System designed to cluster retail customers based on purchasing behavior, demographic attributes, and spending profiles for targeted marketing and cart optimization.

---

## 📌 Features

- **Data Preprocessing & Scaling**: Feature normalization and standardization (StandardScaler / MinMaxScaler).
- **Exploratory Data Analysis (EDA)**: Visual analysis of customer age distribution, annual income, spending scores, and feature correlations.
- **Unsupervised Clustering Algorithms**:
  - **K-Means Clustering**: Determining optimal cluster count $K$ via Elbow Method and Silhouette Analysis.
  - **Hierarchical Clustering**: Dendrogram visualization and agglomerative clustering.
  - **DBSCAN (Density-Based Spatial Clustering)**: Identifying noise points and density-based customer clusters.
- **Cluster Insights & Profiling**: Assigning actionable personas to customer segments (e.g., High-Spenders, Budget Shoppers, Frequent Buyers).

---

## 📁 Repository Structure

```text
SmartCart_Clustering_System/
│── smartcart.ipynb                # Master Clustering & Segmentation Notebook
│── SmartCart Clustering System.pdf# System Architecture & Assignment Documentation
│── .gitignore                     # Excludes raw dataset files and cache
└── README.md                      # Project documentation
```

---

## 📊 Dataset Note

> **Note**: As per repository guidelines, the raw dataset file (`smartcart_customers.csv`) is excluded from this Git repository via `.gitignore`. 
> To run the notebook locally, place `smartcart_customers.csv` in the root folder of the project.

### Expected Data Schema
- `CustomerID`: Unique customer identifier
- `Gender` / `Age`: Demographic information
- `Annual_Income`: Customer annual income
- `Spending_Score`: Quantified spending behavior score (1–100)

---

## 🛠️ Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sauravt20250405/SmartCart.git
   cd SmartCart
   ```

2. **Set Up Python Environment & Dependencies**:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. **Run the Notebook**:
   ```bash
   jupyter notebook smartcart.ipynb
   ```

---

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
