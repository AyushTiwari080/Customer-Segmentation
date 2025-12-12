# 🛍️ Customer Segmentation Project

This project performs **customer segmentation** using unsupervised machine learning techniques on an e-commerce customer dataset. The goal is to identify distinct groups of customers based on their behavior and demographics to help businesses with targeted marketing strategies.

---

## 🧠 Project Overview

Customer segmentation groups customers with similar characteristics, such as spending habits, income, or age. This allows businesses to:

- Tailor marketing campaigns
- Improve customer retention
- Increase revenue by targeting the right audience

In this project, we use clustering techniques (like **K-Means**) to segment customers.

---

## 📁 Dataset

The dataset used is `ecom customer_data.xlsx`, containing customer information:

| Feature | Description |
|---------|-------------|
| CustomerID | Unique identifier for each customer |
| Gender | Male or Female |
| Age | Customer age |
| Annual Income (k$) | Customer’s annual income in thousands |
| Spending Score (1-100) | Customer spending score based on purchasing behavior |

After clustering, results are stored in `Cluster_data.csv`.

---

## 🧰 Tools & Libraries

- **Python**
- **pandas** — for data manipulation
- **numpy** — numerical computations
- **matplotlib** / **seaborn** — data visualization
- **scikit-learn** — machine learning (K-Means)
- **Jupyter Notebook** — project development

---

## 🚀 Methodology

1. **Data Loading**
   - Load `ecom customer_data.xlsx` into a DataFrame
2. **Data Exploration**
   - Inspect data types, check missing values
   - Visualize distributions and relationships
3. **Data Preprocessing**
   - Handle missing or inconsistent data
   - Encode categorical variables if needed
4. **Feature Scaling**
   - Scale numerical features for clustering
5. **K-Means Clustering**
   - Determine optimal number of clusters using the **Elbow Method**
   - Fit K-Means model and assign cluster labels
6. **Results**
   - Save cluster results into `Cluster_data.csv`
   - Visualize clusters using scatter plots (Annual Income vs Spending Score)
7. **Insights**
   - Analyze each cluster to understand customer segments
   - Suggest marketing strategies based on cluster behavior

---

## 📊 Visualizations

- **Elbow Method** to find the optimal number of clusters
- **Scatter plots** of clusters by Annual Income vs Spending Score
- **Cluster profiling** to summarize each segment’s characteristics
  

---

## 📝 How to Run

1. Clone the repository:

```bash
git clone https://github.com/AyushTiwari080/Customer-Segmentation.git
```

2. Navigate to the project folder:

```bash
cd Customer-Segmentation
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Run the Jupyter Notebook:

```bash
jupyter notebook Untitled.ipynb
```

5. View cluster results in Cluster_data.csv.


## 💡 Insights & Recommendations
- **Segment customers based on income and spending habits**
- **Target high-value customers with loyalty programs**
- **Offer personalized promotions to lower-spending clusters**

## 🔮 Future Enhancements
- **Implement Hierarchical or DBSCAN clustering**
- **Incorporate additional features (transaction history and etc)**
- **Deploy as a Streamlit / Dash web application**

