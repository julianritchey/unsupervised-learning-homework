# unsupervised-learning-homework
Module 10 challenge: Crypto clustering

## Find the Best Value for k Using the Original Data
### Code block 11 (line plot)
- Plot depicts a K-means elbow curve for the original dataset.
- Elbow curve is based on ten (10) models ranging from one (1) through ten (10) clusters.

### Question: What is the best value for k?
**Answer:** Four (4).

## Cluster Cryptocurrencies with K-means Using the Original Data
### Code block 17 (scatter plot)
- Plot depicts clusters of price change percentages over 24 hours against price change percentages over seven (7) days.
- Clusters formed by a K-means model on the original dataset.
- Model was generated with four (4) clusters.

## Optimize Clusters with Principal Component Analysis
### Question: What is the total explained variance of the three principal components?
**Answer:** 0.89503166 (sum of 0.3719856, 0.34700813 and 0.17603793)

## Find the Best Value for k Using the PCA Data
### Code block 26 (line plot)
- Plot depicts a K-means elbow curve for the PCA dataset.
- Elbow curve is based on ten (10) models ranging from one (1) through ten (10) clusters.

### Question: What is the best value for k when using the PCA data?
**Answer:** Four (4).

### Question: Does it differ from the best k value found by using the original data?
**Answer:** No, though the elbow is slightly more defined.

## Cluster Cryptocurrencies with K-means Using the PCA Data
### Code block 31 (scatter plot)
- Plot depicts clusters of PC1 data points against PC2 data points.
- Clusters formed by a K-means model on the PCA dataset.
- Model was generated with four (4) clusters.

## Visualise and Compare the Results
### Code block 32 (line plots)
- Plots duplicate the previously-formed elbow curve plots for the original dataset and the PCA dataset.

### Code block 33 (scatter plots)
- Plots duplicate the previously-formed scatter plots for the original dataset and the PCA dataset.

### Question: After visually analysing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-means?
**Answer:** The clusters are more clearly defined and more tightly grouped.

## Other information
- All work can be found in the [crypto_investments.ipynb](https://github.com/julianritchey/unsupervised-learning-homework/blob/main/crypto_investments.ipynb) file.
- All data used in this assignment can be found in the [Resources](https://github.com/julianritchey/unsupervised-learning-homework/tree/main/Resources) folder.