---
description: >-
  A searching on Clustering technique using for mixed datasets, application for
  marketing dataset
---

# Clustering mixed datasets

## A. Paper of Clustering datasets by Sushrut Shendre Apr 29, 2020

[Link](https://towardsdatascience.com/clustering-datasets-having-both-numerical-and-categorical-variables-ed91cdca0677)

* Clustering techniques mean iterates over and over until it attains a state wherein all points of a cluster are similar to each other and dissimilar to all points in different clusters
* The similarity/dissimilar are define by the distance between the points
* Popular Metric to measure this distance:
  * Euclidean distance
  * Manhattan distance
* Both Euclidean and Manhattan distance only works for continuous data, so K-means and hierarchical clustering fail to work for mixed data types.
* To calculate the distance between two entities mixed of categorical and quantitative values, use Gower distance. This distance is scale in a numerical range of 0 \(identical\) and 1 \(maximally dissimilar\).



