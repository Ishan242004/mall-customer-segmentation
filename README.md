# Mall Customer Segmentation using K-Means Clustering
# Project Overview
This project performs customer segmentation on mall customer data using K-Means Clustering. The goal is to group customers based on their behavior such as age, income, and spending score.<br>

# Dataset
File: Mall_Customers.csv<br>
Features used:<br>
Age<br>
Annual Income (k$)<br>
Spending Score (1-100)<br>

# Steps Performed
# 1. Data Analysis (EDA)
Checked null values<br>
Statistical summary<br>
Visualizations:<br>
Age distribution<br>
Gender distribution<br>
Income vs Spending score<br>

# 2. Data Preprocessing
Feature selection<br>
Data scaling using StandardScaler<br>

# 3. Finding Optimal Clusters
Elbow Method (WCSS)<br>
Silhouette Score<br>

Best cluster value found: k = 6

# 4. Model Building
Applied K-Means clustering<br>
Assigned cluster labels to each customer<br>

# 5. Visualization
Cluster visualization (Income vs Spending)<br>
PCA used for 2D cluster visualization<br>

# 6. Cluster Centers
Converted cluster centers back to original scale using inverse transform
