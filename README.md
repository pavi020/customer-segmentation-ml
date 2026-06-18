# customer-segmentation-ml
Customer Segmentation using K-Means Clustering and PCA to identify distinct customer groups based on demographic and spending patterns, enabling data-driven marketing and business decision-making.
# Customer Segmentation using K-Means Clustering and PCA

## 📖 Overview

This project implements **Customer Segmentation** using **K-Means Clustering** and **Principal Component Analysis (PCA)** on the Online Retail dataset. The objective is to identify distinct customer groups based on purchasing behavior and transaction data, enabling businesses to make informed marketing and customer relationship decisions.

The project includes data preprocessing, feature encoding, normalization, dimensionality reduction, clustering, cluster evaluation, and visualization.

---

## 🎯 Objectives

- Clean and preprocess customer transaction data.
- Convert categorical features into numerical values.
- Normalize data for improved clustering performance.
- Reduce dimensionality using PCA.
- Identify customer segments using K-Means Clustering.
- Evaluate clustering quality using multiple metrics.
- Visualize customer groups and uncover behavioral patterns.

---

## 📂 Dataset

The project uses the **Online Retail Dataset**, which contains customer transaction records from an online retail store.

### Features

| Feature | Description |
|----------|-------------|
| InvoiceNo | Invoice Number |
| StockCode | Product Code |
| Description | Product Description |
| Quantity | Quantity Purchased |
| InvoiceDate | Purchase Date and Time |
| UnitPrice | Product Unit Price |
| CustomerID | Customer Identifier |
| Country | Customer Country |

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🔄 Project Workflow

### 1. Data Preprocessing
- Load dataset
- Remove missing values
- Remove invalid records
- Reset indices

### 2. Feature Encoding
- Label Encoding for categorical variables

### 3. Data Normalization
- Min-Max Scaling

### 4. Exploratory Data Analysis
- Histograms
- Pair Plots
- Correlation Heatmaps
- Box Plots

### 5. Principal Component Analysis (PCA)
- Dimensionality reduction to 2 principal components
- Visualization of transformed data

### 6. K-Means Clustering
- Cluster customers into groups
- Determine optimal K using the Elbow Method

### 7. Cluster Evaluation
- Silhouette Score
- Calinski-Harabasz Score
- Davies-Bouldin Score
- WCSS (Within Cluster Sum of Squares)

---

## 📊 Visualizations

The project includes:

- Distribution Plots
- Correlation Heatmap
- PCA Scatter Plot
- Elbow Method Curve
- Cluster Evaluation Graphs
- Box Plots for Outlier Detection

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-segmentation-using-kmeans-and-pca.git
```

Move into the project directory:

```bash
cd customer-segmentation-using-kmeans-and-pca
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the Online Retail dataset.
3. Run all cells sequentially.
4. Analyze cluster visualizations and evaluation metrics.

---

## 📈 Results

- Successfully segmented customers into meaningful groups.
- Reduced dimensionality using PCA for visualization.
- Evaluated cluster performance using multiple clustering metrics.
- Generated insights into customer purchasing behavior.

---

## 💡 Applications

- Customer Behavior Analysis
- Targeted Marketing Campaigns
- Customer Retention Strategies
- Product Recommendation Systems
- Business Intelligence and Decision Support

---

## 🔮 Future Enhancements

- RFM (Recency, Frequency, Monetary) Analysis
- DBSCAN Clustering
- Gaussian Mixture Models
- Interactive Dashboard using Streamlit
- Real-Time Customer Segmentation

---

## 📁 Repository Structure

```text
customer-segmentation-using-kmeans-and-pca/
│
├── Customer_Segmentation.ipynb
├── README.md
├── dataset/
├── images/
└── requirements.txt
```

---

## 👩‍💻 Author

**Pavithra Pramod**

Machine Learning | Data Analytics | Clustering | Customer Segmentation

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
