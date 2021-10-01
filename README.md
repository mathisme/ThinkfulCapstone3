# Unsupervised Learning Capstone: Clustering adults suffering from depression

Unsupervised learning capstone for Thinkful’s Data Science boot camp. 

For the unsupervised learning capstone we needed to go out and find a dataset to perform cluster analysis on.  I chose the 2019 National Health Interview Survey data as the size of the data provided a challenge.  https://www.cdc.gov/nchs/nhis/2019nhis.htm
From the data I chose only those respondants that felt depressed on a weekly or daily basis in order to study how adults suffering from depression might get clustered.
Silhouette score was utilized to evaluate clusters and select the best clustering.

## Included in this repository
* 

## Tools used
* Numpy
* Pandas
* Matplotlib
* Seaborn
* UMAP
* PCA from SciKit-learn
* DBSCAN from SciKit-learn
* Kneed

## To do in the future
* Reorganize the jupyter notebook to better create a slide presentation.  This is my first time using Jupyter to create a slide presentation. After creating the initial presentation, I feel I can improve upon it.
* Try Gaussian Mixture models to cluster the dataset
* Cluster the dataset using the two dimension UMAP data.  As noted the UMAP two-dimensional graph data had seperate clustering.  Because of the loss of information from reducing dimensions, I did not want to cluster this information.  However the data scientist grading my project suggested to use the two dimensional data for clustering.  Therefore in the future I would like to try this.
