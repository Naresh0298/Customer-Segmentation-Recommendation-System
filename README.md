
# Customer Segmentation & Recommendation System

## Overview
This project focuses on **customer segmentation** and **product recommendation** using an e-commerce dataset from Kaggle. The main goal is to identify distinct customer groups based on their purchasing behavior and then build a recommendation system to suggest relevant products to each segment.

## Key Features
- **Data Processing & Feature Engineering**: The project identifies and treats outliers using the **Isolation Forest** algorithm and performs **Recency, Frequency, and Monetary (RFM)** analysis to create essential features for segmentation.
- **Customer Segmentation**: The notebook uses the **K-Means clustering** algorithm to segment customers based on their RFM and other engineered features. The **Elbow Method** and **Silhouette Visualizer** are used to determine the optimal number of clusters.
- **Recommendation System**: The system utilizes **Content-Based Filtering** to recommend products based on item similarities and also generates specific recommendations for each identified customer cluster.

## Technologies Used
* **Python**: The core programming language.
* **Pandas & NumPy**: For data manipulation and numerical operations.
* **Matplotlib, Seaborn, & Plotly**: For data visualization.
* **Scikit-learn**: For machine learning algorithms, including Isolation Forest and K-Means clustering.
* **Kagglehub**: To access the dataset.
