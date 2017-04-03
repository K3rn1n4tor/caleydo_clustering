Caleydo Clustering
==================

This repository is a server-side plugin for Caleydo to apply clustering algorithms on arbitrary matrices.

A live version of this can be accessed here: 

http://ec2-52-58-105-31.eu-central-1.compute.amazonaws.com/stratomex_clustering/


Supported Algorithms:
--------------------
- K-Means (Init methods: Forgy, Uniform, Random, Kmeans++)
- Hierarchical Clustering (Single, Complete, Weighted, Median)
- Affinity Propagation
- Fuzzy Clustering
- Various Distance Measurements(Euclidean, Chebyshef, Manhattan, Pearson, Spearman, ...)

General Information:
-------------------
- All these algorithms expect the input as matrix (or 2D numpy array)
- It is assumed that the matrix is dense (no sparse matrix support right now)
- NaN values will be converted to zero
