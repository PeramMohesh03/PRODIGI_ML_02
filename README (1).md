# PRODIGY_ML_02
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

# Description
The project aims to classify customers using KMeans Clustering Algorithm. After intense analysis of the dataset, the dataset is optimally grouped into 5 clusters. 

![KMeans_5_Clusters_2D](https://github.com/LogeswaranSR/PRODIGY_ML_02/assets/131794661/755cd3f9-ffba-4651-be0d-d408f638770b)

Customers are mainly grouped on the basis of 2 features:

*    Annual Income
*    Spending Score

The mean values of each feature vector in the clusters formed are given below:
|Class  |  Gender  |  Age      |Annual Income (k$)  |Spending Score (1-100)|
|-------|----------|-----------|--------------------|----------------------|
|0      |0.608696  |45.217391  |         26.304348  |             20.913043|
|1      |0.582278  |43.088608  |         55.291139  |             49.569620|
|2      |0.538462  |32.692308  |         86.538462  |             82.128205|
|3      |0.472222  |40.666667  |         87.750000  |             17.583333|
|4      |0.608696  |25.521739  |         26.304348  |             78.565217|

# Dataset
The dataset used is **Mall Customer Segmentation Data**, available in Kaggle. The dataset consists of 4 features, namely:

| # | Column                 | Non-Null Count  |Dtype|
|---|------------------------|-----------------|-----|
| 0 | Gender                 | 200 non-null    |int64|
| 1 | Age                    | 200 non-null    |int64|
| 2 | Annual Income (k$)     | 200 non-null    |int64|
| 3 | Spending Score (1-100) | 200 non-null    |int64|

[Dataset Link](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

