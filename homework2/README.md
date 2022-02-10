# Classifying Digits

## Abstract
Digit classification using the MNIST dataset is often used as the foundation for devel-
oping and evaluating machine learning methods. Using a subset of the MNIST dataset, we train
a classifier to distinguish images of handwritten digits by splitting the dataset into training and
testing data. We can approximate the training data images up to 90% in the Frobenius norm
using the first 16 PCA modes. To train our classifier to distinguish between two digits, we use
scikit-learn’s Ridge regression function for model fitting. The training and testing mean squared
errors are calculated and compared for sets of 2-digit combinations. Although the classifier performs
worse with the pair (3, 8), it generally performs with reasonable accuracy. An extension is to test
our classifier performance if different model fitting methods, such as K-nearest neighbors, random
forest, gradient boosted trees, and support vector machines, is used.
