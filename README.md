# CS231n cheatsheet

# Data-driven approach, Nearest Neighbours, Linear Classification
Slides: http://cs231n.stanford.edu/slides/winter1516_lecture2.pdf

* How does the data-driven approach work?
  - Data-driven approach consists of three performance stages. First one accumulates a dataset of labels and pictures. Second stage trains an image classifier by using Machine Learning. On the third phase an estimation of the image classifier should be implemented.
* What is a nearest neighbour classifier?
  - Nearest Neighbour Classifier is a method of supervised statistical pattern recognition, according to which a new sample is classified by computing the interval to the nearest training case; the sign of that point then determines the classification of the sample. This method is simple, does not need learning and can be applied with few examples, but classification is not fast.
* What is kNN?
  -  The k- Nearest Neighbour is based on getting the k nearest points and assigning the sign of the majority. Usually small and odd k is picked  in order to determine a sample clearly. If k is larger, then it decreases the impact of noisy points within the training data set.
* Give examples for a distance metric.
  - Distance metric is defined by a function of a distance between each pair of elements of a set. A commonly used distance metric for continuous variables is Euclidean distance. The examples of distance metric are given bellow: 
    - Euclidean: Use the standard Euclidean (as-the-crow-flies) distance.
    - Euclidean Squared: Use the Euclidean squared distance in cases where you would use regular Euclidean distance in Jarvis-Patrick or K-Means clustering.
    - Manhattan: Use the Manhattan (city-block) distance.
    - Pearson Correlation: Use the Pearson Correlation coefficient to cluster together genes or samples with similar behavior; genes or samples with opposite behavior are assigned to different clusters.
    - Pearson squared: use the squared pearson correlation coefficient to cluster together genes with similar or opposite behaviors (i.e. genes that are highly correlated and those that are highly anti-correlated are clustered together).
    - Chebychev: use chebychev distance to cluster together genes that do not show dramatic expression differences in any samples; genes with a large expression difference in at least one sample are assigned to different clusters.
    - Spearman: use spearman correlation to cluster together genes whose expression profiles have similar shapes or show similar general trends (e.g. increasing expression with time), but whose expression levels may be very different. 
* What is a hyperparameter?
  -  Hyperparameter is a parameter of a model.
* What data sets are used in a model?
  - For a model training dataset and test dataset are used.
* What are folds for?
* What is cross-validation?
  - Cross-validation (CV) is a method according to which the training set is split into k smaller sets. The following procedure is followed for each of the k “folds”:
   - a model is trained using k-1 of the folds as training data;
   - the resulting model is validated on the remaining part of the data (i.e., it is used as a test set to compute a performance measure such as accuracy).
     The performance measure reported by k-fold cross-validation is then the average of the values computed in the loop.
* What is the accuracy of a model?
  - Accuracy is the proportion of the total number of predictions that were correct.
* What is LDA?
  - Linear discriminant analysis is an approach of feature extraction, which is used for discovering a linear combination of the available features which distinguish the classes.

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

## Authors
* Tim Nieradzik
