# Personalities Test Analysis 📊

This project aims to analyze personality traits based on eye movement features extracted from a dataset containing responses to personality tests. Here, we delve into the realm of data science and machine learning to gain insights into human behavior and characteristics.

## Data Preparation 📑
We start by loading the dataset and handling missing values. Using pandas, we fill missing values with the mean of non-missing values for each label. This ensures our analysis is robust and comprehensive.

## Feature Engineering and Normalization 🛠️
Next, we perform feature engineering to select relevant columns for clustering and machine learning. Eye movement features and personality traits are chosen for further analysis. We normalize the data using StandardScaler to bring all features to the same scale, ensuring unbiased clustering results.

## Clustering Algorithms Comparison 🤖
We explore various clustering algorithms including KMeans, Agglomerative Clustering, DBSCAN, and Gaussian Mixture Models (GMM). Each algorithm is evaluated using silhouette score, Davies-Bouldin score, and Calinski-Harabasz score to determine the optimal clustering approach for our dataset.

## Visualizations 📊
We visualize the distribution of respondents across clusters using a pie chart, providing a clear understanding of how respondents are grouped based on personality traits. Additionally, we identify the dominant personality type in each cluster, offering valuable insights into the clustering results.

Through this project, we gain valuable insights into personality traits and behavior patterns. By leveraging data science techniques and machine learning algorithms, we unravel hidden patterns within the dataset, paving the way for deeper understanding and future research in the field of psychology and human behavior.
