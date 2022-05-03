# Principle Component Analysis

## Definition

Principal component analysis (PCA) is a technique that transforms high-dimensions data into lower-dimensions while retaining as much information as possible.

![alt](https://miro.medium.com/max/1192/1*QinDfRawRskupf4mU5bYSA.png)

![alt](https://miro.medium.com/max/1400/1*LKTwaVmP4Dqxb-N3iD3CHw.png)

PCA is extremely useful when working with data sets that have a lot of features. Common applications such as image processing, genome research always have to deal with thousands-, if not tens of thousands of columns.

While having more data is always great, sometimes they have so much information in them, we would have impossibly long model training time and the curse of dimensionality starts to become a problem. Sometimes, less is more.

## How does PCA work?

Step 1: Standardize the dataset.

Step 2: Calculate the covariance matrix for the features in the dataset.

Step 3: Calculate the eigenvalues and eigenvectors for the covariance matrix.

Step 4: Sort eigenvalues and their corresponding eigenvectors.

Step 5: Pick k eigenvalues and form a matrix of eigenvectors.

Step 6: Transform the original matrix.

# Datasets

## Palmer Penguins

source: https://github.com/allisonhorst/penguins

Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. Both datasets contain data for 344 penguins. There are 3 different species of penguins in this dataset, collected from 3 islands in the Palmer Archipelago, Antarctica.

## sklearn.datasets.load_wine

The wine dataset is a classic and very easy multi-class classification dataset.
The copy of UCI ML Wine Data Set dataset is downloaded and modified to fit
standard format from:
https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data

# Reference

https://towardsdatascience.com/principal-component-analysis-pca-explained-visually-with-zero-math-1cbf392b9e7d

https://docs.w3cub.com/scikit_learn/modules/generated/sklearn.datasets.load_wine#sklearn.datasets.load_wine
