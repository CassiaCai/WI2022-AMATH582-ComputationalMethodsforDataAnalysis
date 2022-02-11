# Classifying Digits

## Abstract
Digit classification using the MNIST dataset is often used as the foundation for devel-
oping and evaluating machine learning methods. Using a subset of the MNIST dataset, we train a
classifier to distinguish images of handwritten digits. We can approximate the training data images
up to 90% in the Frobenius norm using the first 14 PCA modes. However, after applying Standard-
Scaler, which standardizes by removing the mean and scaling to unit variance, 90% is approximated
using 16 modes. To train our classifier, we use scikit-learn’s Ridge regression function for model
fitting. The training and testing mean squared errors are compared for sets of 2-digit combinations.
Although the classifier performs worse with the pair (3, 8), it generally performs with reasonable
accuracy. An extension is to test our classifier performance using different model fitting methods,
like K-nearest neighbors, random forest, and gradient boosted trees, and support vector machines.
