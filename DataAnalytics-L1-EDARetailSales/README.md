# Customer Segmentation Analysis

## Project Overview
This project performs customer segmentation using RFM Analysis and K-Means Clustering on the UCI Online Retail Dataset.

## Objective
To group customers based on their purchasing behavior and identify valuable customer segments.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Cleaning
- Removed missing Customer IDs.
- Removed duplicate records.
- Removed cancelled transactions.
- Removed invalid quantities and prices.

## Analysis Performed
- RFM Analysis (Recency, Frequency, Monetary)
- Feature Standardization using StandardScaler
- Elbow Method
- K-Means Clustering
- Customer Cluster Profiling
- Scatter Plot Visualizations
- Customer Count Bar Chart

## Key Findings
- Total Customers Analyzed: 4,338
- Number of Clusters: 3
- Cluster 0: At-Risk Customers
- Cluster 1: Regular Customers
- Cluster 2: VIP / High-Value Customers

## Conclusion
K-Means clustering successfully segmented customers into three groups. These insights can help businesses improve customer retention and create targeted marketing strategies.

## Dataset
UCI Online Retail Dataset – https://archive.ics.uci.edu/dataset/352/online+retail