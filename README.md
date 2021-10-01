# Unsupervised Learning Capstone: Clustering adults suffering from depression

Unsupervised learning capstone for Thinkful’s Data Science boot camp. 

For the unsupervised learning capstone we needed to go out and find a dataset to perform cluster analysis on.  I chose the 2019 National Health Interview Survey data as the size of the data provided a challenge.  https://www.cdc.gov/nchs/nhis/2019nhis.htm
From the data I chose only those respondants that felt depressed on a weekly or daily basis in order to study how adults suffering from depression might get clustered.

Silhouette score was utilized to evaluate clusters and select the best clustering.

## Included in this repository
* capstone.ipynb -- the main notebook
* capstone.slides.html -- the slide presentation
* vars.csv -- a csv file I created listing the variables I intended to use

## Project Features
* An exploratory data analysis on data involving depression, demographics, and chronic conditions
* Visualizing subsets of the data in two dimensions using both PCA and UMAP
* Attempting and analyzing Kmeans and DBSCAN clustering on various subsets of the data
* Evaluating kmeans clustering and DBSCAN clustering using silhouette score and knowledge of what constitutes good clustering with respect to DBSCAN
* Selecting, visualizing and analyzing the final group of clusters.

## Discoveries/Reflections
* As the data came from a general health survey and not a survey targeted to depression, clusters were mixing.  
* As noted below, there was a clear seperation of clusters in the two dimensional visualizations, I should have tried clustering this reduced data

## Tools used
* Numpy
* Pandas
* Matplotlib
* Seaborn
* UMAP
* PCA from SciKit-learn
* DBSCAN from SciKit-learn
* Kmeans from Scikit-learn
* Kneed

## To do in the future
* Reorganize the jupyter notebook to better create a slide presentation.  This is my first time using Jupyter to create a slide presentation. After creating the initial presentation, I feel I can improve upon it.
* Try Gaussian Mixture models to cluster the dataset
* Cluster the dataset using the two dimension UMAP data.  As noted the UMAP two-dimensional graph data had seperate clustering.  Because of the loss of information from reducing dimensions, I did not want to cluster this information.  However the data scientist grading my project suggested to use the two dimensional data for clustering.  Therefore in the future I would like to try this.
