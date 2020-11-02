# Unsupervised Clustering of Citation Graph

Project which expands on the third coursework of the Methods for Data Science module I took as part of my MSc Applied Mathematics at Imperial College London.

In this task I conducted the unsupervised clustering of text documents with an associated citation graph. I used the the k-means and modularity maximisation methods to create the clusters. I aditionally investigated the underying graph which included the computation of the degree, betweeness and edge centralities.

The data used is the Cora data set where each sample in the dataset corresponds to a journal paper in some scientific discipline. The text in each paper has been summarised as a high-dimensional vector of p features, where each (binary) coordinate of the vector indicates the presence or absence of a particular word within the text of the paper. The size of the dictionary for this dataset is 1433 words.

The dataset contains N=2485 papers, and each paper is described by a p-dimensional vector of features (p=1433). This dataset is given as an $N \times p$ feature matrix, F.

We also have information about citations between papers. The citations define an undirected graph which is encoded through its $N \times N$ adjacency matrix, A.
