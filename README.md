# PRML
This repository contains assignments/projects done in the course CS5691 Pattern Recognition and Machine Learning. The assignments involved implementation of ML algorithms from scratch without using publicly available libraries (except numpy and pandas). More info can be found in the reports present in each folder.
# PCA and K-means clustering
In this assignment, PCA was performed from scratch using numpy and pandas on the MNIST dataset. The principal components (i.e the eigen-vectors of the covariance matrix) were computed and shown as below.
![image](https://github.com/tharrunkumar2020/PRML/assets/108512265/25f20938-8291-4833-8c32-92e6109654f1)
Further they were reconstructed using the first few principal components, thus achieving dimensionality reduction for downstreaam tasks (d represents the number of principal components used). Thus a 28x28 image that required 784 features were reduced to around 60-70 features for downstream tasks.
![image](https://github.com/tharrunkumar2020/PRML/assets/108512265/e2ba5263-b715-4e63-a576-c059bf0e6564)
Further, Kernel methods were used to caputure the non-linearity of the dataset. This was done using the RBF(Radial Basis Function) Kernel, and Polynomial Kernel.

K-means Clustering was performed on the crescent moon dataset and the following result was obtained.
![image](https://github.com/tharrunkumar2020/PRML/assets/108512265/69311644-a310-43c6-9110-5da64453cddc)
Further spectral clustering methods were employed to capture the non-linearity of the dataset, using RBF kernel and polynomial kernel.
# Regression
In this assignment, linear regression was done on a dataset with 100 features and 10,000 entries. It was done using the normal equations method , gradient descent method and stochastic gradient descent method.

Ridge regression was also performed with 5-fold cross validation and found to have best results on the test data.
# Spam Detection
Using the Kaggle dataset, a spam classifier was built. First, the emails were preprocessed by removing stopwords, punctuations, etc. Then a count vectorizer was implemented using numpy. Then, the classifier was built using : Naive Bayes and Logistic Regression. Out of these, logistic regression gave the highest accuracy.
