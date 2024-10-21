# 🛍️ Mall Customers Segmentation

Welcome to the **Mall Customers Segmentation** project! This project focuses on clustering mall customers based on their **Annual Income** and **Spending Score** using the **K-Means Clustering Algorithm**. The goal is to uncover meaningful customer segments that can help businesses understand their audience better and tailor marketing strategies accordingly.

## 📊 Project Overview

Customer segmentation is crucial for businesses to identify different groups within their customer base. In this project, we use the popular **K-Means clustering** algorithm to segment customers into distinct groups. By analyzing customer behavior, this project provides insights into which customers are high spenders, which ones are budget-conscious, and much more.

## 🚀 Features

- **Data Preprocessing:** We clean the data, drop unnecessary columns, and encode categorical variables.
- **Data Visualization:** Histograms and heatmaps to explore data distribution and correlation between features.
- **Clustering with K-Means:** We use the Elbow Method to determine the optimal number of clusters and apply K-Means for segmentation.
- **Cluster Visualization:** Beautiful 2D scatter plots with cluster centroids marked in red.

## 📂 Dataset

The dataset used is the **Mall Customer Segmentation Data**, which you can find on Kaggle:

- [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The dataset includes:
- **CustomerID**: Unique customer identifier (not used for clustering)
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income**: Customer's annual income in $1000s
- **Spending Score**: Customer’s spending score (1-100)

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/smebad/mall-customers-segmentation.git
   ```
## 🛠️ Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning algorithms (K-Means and Label Encoding).

## 📈 Clustering Results
We segmented the customers into 5 distinct clusters based on their Annual Income and Spending Score:

- **Cluster 1** (Low Income, Low Spending)
- **Cluster 2** (Low Income, High Spending)
- **Cluster 3** (High Income, Low Spending)
- **Cluster 4** (High Income, High Spending)
- **Cluster 5** (Moderate Income & Spending)
Each cluster represents a group of customers with similar spending behaviors, which can help businesses in creating more personalized marketing strategies.

## 📊 Elbow Method
The Elbow Method was used to find the optimal number of clusters. Based on the elbow point in the WCSS plot, 5 clusters were selected as the optimal number.

## 📜 How to Use
1. Explore the Data: Run the notebook to load and explore the dataset.
2. Train the Model: Use the provided K-Means clustering algorithm to segment the customers.
3. Visualize the Results: Visualize the clusters using scatter plots.

## 💡 Insights
- **Valuable Customers**: High-income, high-spending customers (Cluster 4) are the most valuable and can be targeted for premium services.
- **Budget-Conscious Customers**: Low-income, high-spending customers (Cluster 2) are frequent shoppers despite a lower income.
- **Potentially Engaged Customers**: Moderate-income customers in Cluster 5 might respond well to personalized offers.

## ✨ Conclusion
By the end of this project, we've successfully segmented mall customers into meaningful groups using K-Means clustering. These clusters provide actionable insights that businesses can leverage to create more effective marketing strategies and improve customer satisfaction.

## ⭐If you found this project helpful, feel free to give it a star on GitHub!
