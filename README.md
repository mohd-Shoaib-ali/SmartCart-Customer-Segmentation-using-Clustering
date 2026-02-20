# SmartCart-Customer-Segmentation-using-Clustering
SmartCart – Customer Segmentation using Clustering.
Problem Statement
=================
E-commerce companies need to understand customer behavior to design personalized marketing strategies.
This project performs customer segmentation using unsupervised learning techniques.

Dataset Features
================
Income

Age

Recency

Total Spending

Children count

Education

Living status

🛠 Techniques Used
==================

Data Cleaning & Feature Engineering

OneHot Encoding

Standard Scaling

PCA (Dimensionality Reduction)

KMeans Clustering

Agglomerative Clustering

Elbow Method

Silhouette Score

📈 Model Selection
=====================
Optimal number of clusters selected using:

Elbow Method

Silhouette Score

Final clusters: 4

Cluster Insights
🔹 Cluster 0 – Discount-Oriented Family Shoppers
===============
Key Characteristics:

More children

Lower overall response to campaigns

Mostly family-based shoppers

Higher web visits

Prefer discounts and promotional offers

Moderate income and moderate spending

Business Insight:
These customers are price-sensitive family buyers. They respond better to discount campaigns rather than premium promotions.

Recommended Strategy:

Offer bundle discounts

Promote family deals

Provide seasonal sales offers

🔹 Cluster 1 – High-Value Loyal Customers
=============
Key Characteristics:

Fewer children

Slightly older age group

Good campaign response

High income and high spending

Active across store, catalog, and web purchases

Likely partnered

Business Insight:
This is a premium customer segment with strong purchasing power and good responsiveness to marketing.

Recommended Strategy:

Loyalty programs

Exclusive memberships

Personalized recommendations

Early access to new products

🔹 Cluster 2 – Private, Low-Spending Families
==============
Key Characteristics:

More children

Average campaign response

Some purchases made alone

Increased web visits

Low income and low spending

Very responsive to heavy discount coupons

Business Insight:
This segment is budget-constrained and highly price-sensitive. They engage when strong discounts are available.

Recommended Strategy:

High-discount coupon campaigns

Cashback offers

Budget-friendly product recommendations

🔹 Cluster 3 – Premium Single Shoppers (Best ROI Segment)
===============
Key Characteristics:

Fewer children

Slightly older

Best campaign response rate

High income and high spending

Likely single

Moderate web usage

Active in store, catalog, and web purchases

Business Insight:
This is the most profitable segment with the highest response rate and strong purchasing power.

Recommended Strategy:

Premium services

High-end product promotions

Personalized luxury campaigns

VIP access programs.
CONCLUSION:
===========
Cluster 1 and Cluster 3 represent high-value customer segments, while Cluster 0 and Cluster 2 are price-sensitive segments that respond better to discount-driven strategies.
To RUN CODE
============
pip install -r requirements.txt
jupyter notebook
