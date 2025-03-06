# CryptoClustering

## Overview
This project focuses on clustering cryptocurrencies using **K-Means Clustering** and optimizing the clusters with **Principal Component Analysis (PCA)**. The goal is to explore how dimensionality reduction impacts clustering performance and interpretability.

## Technologies Used
- **Python**
- **Pandas**: For data manipulation
- **hvPlot**: For interactive visualizations
- **scikit-learn**: For K-Means clustering and PCA
- **StandardScaler**: For feature normalization

## Project Workflow
1. **Data Preparation**
   - Load and explore cryptocurrency market data.
   - Normalize the data using `StandardScaler`.
   
2. **Finding Optimal Clusters**
   - Use the **Elbow Method** to determine the best `k` value.
   - Apply K-Means clustering on the original dataset.

3. **Dimensionality Reduction with PCA**
   - Reduce features to three principal components.
   - Analyze how much variance is retained.

4. **K-Means Clustering with PCA Data**
   - Repeat the clustering process using PCA-transformed data.
   - Compare the clustering results with and without PCA.

5. **Visualization & Analysis**
   - Compare the elbow curves of the original and PCA data.
   - Plot and contrast cluster distributions.
   - Discuss insights from reducing dimensions before clustering.

## Key Findings
- The **Elbow Method** suggested an optimal `k` value of **4** for the original dataset and **3-4** for PCA-transformed data.
- PCA reduced feature complexity while retaining **85-90% of variance**, making clustering more efficient.
- Clustering on PCA data resulted in more distinct groupings, showing the benefits of dimensionality reduction.

## Acknowledgments
I would like to express my sincere gratitude to **my instructor** for providing valuable guidance throughout this project. Your insights and support were instrumental in understanding clustering techniques and their applications.

Thank you for your time and support!

---



