# 🛍️ Customer Segmentation using K-Means Clustering (Unsupervised Learning)

This project applies an unsupervised learning technique (K-Means Clustering) to segment mall customers based on their **annual income** and **spending score**. The goal is to uncover patterns in customer behavior to help businesses develop targeted marketing strategies and improve resource allocation.

## 📊 Problem Statement
Businesses often lack a structured approach to classify customers, which results in generalized marketing efforts. This project addresses the challenge by applying K-Means Clustering to identify meaningful customer segments, enabling more personalized business strategies.

## 🗂️ Dataset Description
The dataset contains the following columns:
- `customer_id`
- `gender`
- `age`
- `annual_income` (k$)
- `spending_score` (1-100)

No missing or duplicated values were present. Column names were standardized to lowercase with underscores for coding convenience.

## 🚀 Methodology
- **Features Used:** `annual_income`, `spending_score`
- **Feature Scaling:** StandardScaler
- **Clustering Algorithm:** K-Means Clustering
- **Number of Clusters (k):** 5 (determined via Elbow Method)
- **Libraries Used:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 📈 Results & Insights
The K-Means Clustering algorithm segmented customers into **5 distinct clusters**, revealing different purchasing behaviors:
- High-income high-spenders
- Low-income high-spenders
- High-income moderate-spenders
- Moderate-income average-spenders
- Low-income low-spenders

These insights enable businesses to implement data-driven marketing strategies and improve customer relationship management.

## 📑 Project Files
- Colab Notebook woth code and Visualizations
https://github.com/ZainabBee24/customer-segmentation-kmeans/tree/main

- Full Project Documentation 
https://github.com/ZainabBee24/customer-segmentation-kmeans/blob/main/Unsupervised_Learning_Project.ipynb%20-%20Colab.pdf

## 🖥️ Run the Notebook on Google Colab
[![ https://colab.research.google.com/github/ZainabBee24/customer-segmentation-kmeans/blob/main/Unsupervised_Learning_Project.ipynb]]

## 📬 Contact
**Zainab Balarabe Adam**  
Email: adamzainabb1@gmail.com
LinkedIn: https://www.linkedin.com/in/zainab-b-adam1 
