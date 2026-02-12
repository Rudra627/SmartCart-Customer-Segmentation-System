<h1>SmartCart Customer Segmentation System</h1>
SmartCart is an e-commerce platform with 2240+ customer records and 22 attributes including demographics, purchase behavior, engagement activity, and loyalty indicators.

The company was using generic marketing strategies without understanding different customer behavior patterns.

This project builds an intelligent customer segmentation system using K-Means clustering to identify meaningful customer groups for targeted marketing and retention strategies.

🎯 Problem Statement

Design an unsupervised machine learning system that:

Analyzes customer transaction and engagement data

Groups customers into meaningful clusters

Supports data-driven marketing decisions

📂 Dataset Description

Each row represents a customer with features including:

👤 Demographics

Year_Birth

Education

Marital_Status

Income

Kidhome

Teenhome

🛍 Purchase Amount

MntWines

MntFruits

MntMeatProducts

MntFishProducts

MntSweetProducts

MntGoldProds

🛒 Purchase Frequency

NumDealsPurchases

NumWebPurchases

NumCatalogPurchases

NumStorePurchases

NumWebVisitsMonth

🔁 Customer Feedback

Recency

Complain

🧠 Approach
1️⃣ Data Preprocessing

Removed irrelevant features (ID, dates)

Handled missing values

Feature engineering

Feature scaling using StandardScaler

2️⃣ Optimal Cluster Selection

Applied Elbow Method

Evaluated WCSS

Selected optimal K

3️⃣ Model Building

Implemented K-Means clustering

Assigned cluster labels

Analyzed cluster distribution

4️⃣ Visualization

Elbow plot

3D cluster visualization

Cluster count distribution

📊 Key Results

Identified distinct customer segments

Observed clear separation between clusters

Found variation in cluster sizes

Extracted business-relevant customer groups

💡 Business Insights

Cluster examples:

High-income, high-spending customers (Premium Segment)

Discount-sensitive shoppers

Moderate engagement customers

Low engagement / potential churn segment

These insights can help:

Improve targeted marketing

Increase customer retention

Optimize promotional campaigns

Improve revenue strategies

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn
