# Customer Segmentation Clustering

## Overview
This project focuses on segmenting customers based on their shopping behavior and demographics using clustering techniques. The goal is to identify distinct customer groups such as High Spenders, Loyal Customers, Discount Seekers, and Low Engagement Users, enabling data-driven marketing and personalized business strategies.

The dataset is automatically loaded from a public CSV file hosted on GitHub, ensuring easy reproducibility.

## Dataset
Dataset used: [Mall Customers Dataset](https://gist.github.com/GaneshSparkz/9dabfdeab9808d8e1b74f7fad4b91253)  
Typical columns:  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  
- Optional metadata (CustomerID, Gender) — removed for clustering  

## Features / Steps
1. Load dataset automatically from GitHub  
2. Clean and preprocess data (handle missing values, remove non-numeric columns)  
3. Scale features using StandardScaler  
4. Determine optimal number of clusters using Elbow method  
5. Apply **K-Means clustering**  
6. Visualize clusters via scatter plots and pairplots  
7. Summarize cluster statistics and interpret segments  
8. Save clustered dataset for further analysis  

## How to Run
1. Clone the repository  
2. Open the Jupyter or Google Colab notebook  
3. Run all cells — dataset will be automatically loaded and clustering performed  

## Libraries Used
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

## Insights & Business Use
After clustering, each segment can be labeled (e.g., High Spenders, Discount Seekers, Low Engagement). These segments can inform marketing campaigns, loyalty programs, personalized offers, and customer retention strategies.
