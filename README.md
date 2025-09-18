# Credit Card Segmentation using K-Means Clustering

## Project Overview
This project segments credit card holders into distinct groups based on their usage patterns. By identifying these customer segments, a bank can develop targeted marketing strategies.

## Dataset
The dataset used is "CC GENERAL.csv," which contains information about customer spending habits. The data can be found on [Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata).

## Methodology
- **Data Cleaning:** Handled missing values using mean imputation.
- **Feature Scaling:** Used `StandardScaler` to normalize the features.
- **Clustering:** Applied the K-Means algorithm to group customers into 8 distinct clusters.
- **Cluster Analysis:** Analyzed the mean values of features for each cluster to understand their characteristics.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook