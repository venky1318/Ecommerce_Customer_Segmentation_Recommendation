# E-Commerce Customer Segmentation & Recommendation Analysis

## 1. Project Overview

This project analyzes e-commerce customer purchasing behavior using Machine Learning.

It applies RFM analysis and K-Means clustering to identify different customer segments based on purchasing patterns.

A basic product recommendation system is also developed using Cosine Similarity to recommend products based on customer purchase history and product similarity.

## 2. Objectives

- Analyze customer purchasing behavior.
- Clean and preprocess transaction data.
- Calculate Recency, Frequency and Monetary features.
- Perform customer segmentation using K-Means.
- Visualize customer clusters.
- Develop a product recommendation component.
- Generate business recommendations for customer segments.

## 3. Dataset

**Dataset:** UCI Online Retail Dataset

Source: https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains online retail transactions, including customer IDs, product descriptions, invoice numbers, quantities, prices, dates and countries.

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Cosine Similarity
- Google Colab

## 5. Project Workflow

1. Dataset collection.
2. Data exploration.
3. Data cleaning.
4. Exploratory Data Analysis.
5. RFM feature engineering.
6. Feature scaling.
7. Elbow Method.
8. Silhouette Analysis.
9. K-Means clustering.
10. Customer segment profiling.
11. Product similarity calculation.
12. Product recommendations.
13. Business recommendations.
14. Model evaluation and export.

## 6. Customer Segmentation

RFM analysis is used to understand customer behavior.

- Recency: Time since the latest purchase.
- Frequency: Number of unique purchases.
- Monetary: Total customer spending.

K-Means clustering is applied to group customers into four initial clusters.

Customer profiles are interpreted using their RFM characteristics.

## 7. Recommendation System

Cosine Similarity is used to measure the similarity between products based on customer purchasing patterns.

The system recommends products that are similar to products previously purchased by customers.

## 8. Evaluation

Clustering performance is examined using:

- Elbow Method.
- Silhouette Score.
- Cluster distribution.
- RFM cluster profiles.

Actual evaluation results are available in evaluation_summary.csv.

## 9. Business Applications

- Customer retention.
- Customer loyalty programs.
- Personalized product recommendations.
- Targeted marketing campaigns.
- Customer engagement.
- E-commerce sales analysis.

## 10. Project Structure

The repository includes the Jupyter Notebook, cleaned datasets, RFM features, customer segments, recommendation outputs, trained model, visualizations and project report.

## 11. Conclusion

This project demonstrates how unsupervised Machine Learning can be used to understand e-commerce customer purchasing behavior.

RFM analysis and K-Means clustering help identify meaningful customer groups, while Cosine Similarity provides a basic product recommendation component.

The project provides practical experience in data preprocessing, customer analytics, clustering and recommendation systems.

## 12. Future Enhancements

- Implement collaborative filtering.
- Develop a web-based recommendation dashboard.
- Compare multiple clustering algorithms.
- Improve recommendation ranking.
- Add real-time customer recommendations.
