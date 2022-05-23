# CryptoClusteringM10

This program demonstrates two models for unsupervised learning. KMeans and dimensional reduction using PCA analysis.

Technologies

This project is written in python. The required libraries are as follows pathlib ver 2.3.6, pandas, hvplots.pandas, sklearn.cluster, sklearn.decomposition, sklearn.preprocessing

Usage

The application demonstrates the usage of KMeans and reducing dimensions using PCA analysis

Analysis Report

Reducing the dimensions to 3 PCA explains 89.5% or variance. The number of clusters, i.e. k did not change. It is still at 4. However, the clustering of data has changed. The original clusers were based on 7d price change v.s. 24h price change, however, the PCA cluster graphs is based on PCA1 and PCA2, which explains 72% of variance. The change in clustering is due to that. But the clusters in PCA graphs are tigher with lower inertia.
