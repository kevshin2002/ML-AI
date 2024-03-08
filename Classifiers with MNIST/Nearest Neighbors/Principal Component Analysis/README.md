# Principal Component Analysis
We utilize Principal Component Analysis to feature optimize and reduce the number of vectors needed so that we minimize complexity and computation.

## Principal Values for Data
![PCA Data](./imgs/PCA%20Data.png)

## Principal Values for Class 5
![PCA Five](./imgs/PCA%20Five.png)

## Optimal Subspace Dimension
To minimize error rate, I proposed using n = 72, as that's when the principal values drop below 0.1. Such values are negligible and does not contribute to the weighting of classifications.

We can see below in the graph that it converges to 0 at approximately 72.

![Graph PCA](./imgs/PCA%20Graph.png)

For the class five, we can also find out when the optimal dimensionality is.

![Graph PCA Five](./imgs/PCA%20Graph%20Five.png)

## No Classification
Due to an issue with coding and getting dimensions to line up, the code ended up not being finished. Might implement some day when given time.