# Cx_segmentation
Customer Segmentation using K-Means Clustering on Online Retail Data to identify customer groups based on purchasing behavior (Recency, Frequency, Monetary).

# Customer Segmentation using K-Means Clustering

## Overview
This project performs customer segmentation on an online retail dataset using **unsupervised machine learning (K-Means Clustering)**.  

The goal is to identify distinct groups of customers based on their purchasing behavior and help businesses design targeted marketing strategies.

---

## Problem Statement
Retail businesses often struggle to identify different types of customers.  
This project uses **RFM analysis (Recency, Frequency, Monetary)** combined with **K-Means clustering** to group customers with similar purchasing patterns.

---

## Dataset
The dataset contains online retail transaction data including:

- Invoice Number
- Stock Code
- Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## Project Workflow
1. **Data Exploration**
   - Understanding dataset structure
   - Identifying anomalies and invalid stock codes

2. **Data Cleaning**
   - Removing invalid transactions
   - Handling missing values
   - Filtering irrelevant records

3. **Feature Engineering**
   - Creation of **RFM features**
   - Standard scaling of features

4. **Modeling**
   - Applied **K-Means Clustering**
   - Determined optimal clusters

5. **Customer Segmentation**
   - Retain (High value customers)
   - Re-Engage (Inactive customers)
   - Nurture (Low engagement customers)
   - Reward (Highly loyal customers)

6. **Visualization**
   - Cluster visualization
   - Customer behavior patterns

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Insights
- Identified **4 main customer segments**
- High-value loyal customers require retention strategies
- Low-engagement customers require targeted marketing campaigns

---

## Business Impact
Customer segmentation helps businesses:

- Improve targeted marketing
- Increase customer retention
- Optimize promotional campaigns
- Maximize revenue from loyal customers


