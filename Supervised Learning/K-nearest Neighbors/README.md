# k-Nearest Neighbors

## Definition

The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems.
Note: An understanding of how we calculate the distance between points on a graph is necessary before moving on. If you are unfamiliar with or need a refresher on how this calculation is done, thoroughly read “Distance Between 2 Points” in its entirety, and come right back.

There are other ways of calculating distance, and one way might be preferable depending on the problem we are solving. However, the straight-line distance (also called the Euclidean distance) is a popular and familiar choice.

The KNN Algorithm

1.Load the data

2.Initialize K to your chosen number of neighbors

3.For each example in the data

(a)Calculate the distance between the query example and the current example from the data.

(b)Add the distance and the index of the example to an ordered collection


4. Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances

5. Pick the first K entries from the sorted collection

6. Get the labels of the selected K entries

7. If regression, return the mean of the K labels

8. If classification, return the mode of the K labels

## Advantages

The algorithm is simple and easy to implement.

There’s no need to build a model, tune several parameters, or make additional assumptions.

The algorithm is versatile. It can be used for classification, regression, and search (as we will see in the next section).

# Dataset

## Palmer penguins dataset

Datasets contain data for 344 penguins. There are 3 different species of penguins in this dataset, collected from 3 islands in the Palmer Archipelago, Antarctica. Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

# References

https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761
