# Mall Customer Segmentation using K-Means Clustering
# Project Overview
This project performs customer segmentation on mall customer data using K-Means Clustering. The goal is to group customers based on their behavior such as age, income, and spending score.

# Dataset
File: Mall_Customers.csv
Features used:
Age
Annual Income (k$)
Spending Score (1-100)

# Steps Performed
# 1. Data Analysis (EDA)
Checked null values
Statistical summary
Visualizations:
Age distribution
Gender distribution
Income vs Spending score

# 2. Data Preprocessing
Feature selection
Data scaling using StandardScaler

# 3. Finding Optimal Clusters
Elbow Method (WCSS)
Silhouette Score

Best cluster value found: k = 6

# 4. Model Building
Applied K-Means clustering
Assigned cluster labels to each customer

# 5. Visualization
Cluster visualization (Income vs Spending)
PCA used for 2D cluster visualization

# 6. Cluster Centers
Converted cluster centers back to original scale using inverse transform
