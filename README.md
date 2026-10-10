# Week_3_Unsupervised_Learning_Clustering_Analysis
Week 3 Data Science internship project on unsupervised learning and customer segmentation using K-Means clustering, Python, data visualization, and the Mall Customer Segmentation dataset.
# Week 3: Unsupervised Learning and Clustering Analysis

## Project Overview

This project was completed as part of the Virtual Data Science with Python internship at YuvaIntern. The main objective is to apply unsupervised learning techniques to a customer dataset and identify meaningful customer segments using clustering.

## Objectives

- Explore and understand the Mall Customer Segmentation dataset.
- Perform data inspection and preprocessing.
- Apply feature scaling using StandardScaler.
- Implement K-Means clustering using Python.
- Explore the number of clusters using the Elbow Method and Silhouette Score.
- Visualize customer groups and interpret their characteristics.
- Discuss potential business applications of customer segmentation.

## Dataset

**Dataset Name:** Mall Customer Segmentation Data

**Source:** [Kaggle — Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The dataset contains 200 customer records and five columns: CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1–100).

For clustering, the analysis focuses on Annual Income and Spending Score.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology

1. Load and inspect the dataset.
2. Check data quality, including missing values and duplicate records.
3. Select Annual Income and Spending Score as clustering features.
4. Standardize the selected features using StandardScaler.
5. Examine suitable cluster numbers using the Elbow Method and Silhouette Score.
6. Apply K-Means clustering with five clusters.
7. Visualize the clusters and cluster centres.
8. Summarize and interpret customer segments.

## Results

The final analysis uses five clusters (K = 5) and reports a Silhouette Score of 0.555.

The identified customer segments are:

- Cluster 0: Moderate income and moderate spending.
- Cluster 1: High income and high spending.
- Cluster 2: Low income and high spending.
- Cluster 3: High income and low spending.
- Cluster 4: Low income and low spending.

These groups can help explore customer behaviour and potential marketing strategies.

## Business Applications

Customer segmentation can support personalized marketing, customer loyalty programmes, promotional planning, and better understanding of different spending patterns.

## Limitations

The analysis uses only two features for clustering. The results are exploratory and may change with different features, preprocessing choices, or cluster settings.

## Conclusion

This project demonstrates the use of K-Means clustering for customer segmentation and provides practical experience in data preprocessing, model evaluation, visualization, and interpretation.

## Project Deliverables

- Jupyter Notebook containing the Python analysis.
- Cluster visualizations and evaluation graphs.
- Cluster summary and interpretation.
- Project report in DOCX format.

## Author

Nandita Manna

Virtual Data Science with Python Internship — YuvaIntern
