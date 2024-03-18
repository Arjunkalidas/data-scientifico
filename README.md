# data-scientifico

This project started out of my curiosity for learning machine learning, statistics and artificial intelligence and its many possibilities. My intention is to maintain this repository as a journal to update my data science journey.

## Introduction

### Machine Learning (ML):
Machine learning is a subfield of artificial intelligence (AI) that focuses on developing algorithms and techniques that enable computers to learn from data and make predictions or decisions without being explicitly programmed to do so. ML algorithms can identify patterns, learn from past experiences, and improve their performance over time. Common tasks in machine learning include classification, regression, clustering, and reinforcement learning.

### Statistics:
Statistics is a branch of mathematics that deals with collecting, analyzing, interpreting, and presenting data. It provides methods and techniques for summarizing data, making inferences or predictions based on data, and evaluating the reliability of these conclusions. Statistical concepts such as probability, hypothesis testing, regression analysis, and sampling are widely used in various fields, including machine learning and artificial intelligence, to draw meaningful insights from data.

### Artificial Intelligence (AI):
Artificial intelligence is a broad field of computer science that focuses on creating intelligent machines capable of simulating human-like intelligence and behavior. AI encompasses a wide range of techniques, including machine learning, natural language processing, computer vision, robotics, and expert systems. The goal of AI is to develop systems that can perceive, reason, learn, and adapt to new situations, ultimately enabling them to perform tasks that typically require human intelligence.

## Machine Learning Algorithms

This repository is for data science learning, and implementations of various ML algorithms, such as:

#### Linear Regression:
Linear regression is a supervised learning algorithm used for predicting the value of a continuous target variable based on one or more input features. It assumes a linear relationship between the input features and the target variable, represented by a straight line in two dimensions or a hyperplane in higher dimensions. The algorithm aims to find the best-fitting line or plane that minimizes the difference between the actual and predicted values. Linear regression is widely used for tasks such as predicting house prices, stock prices, or sales forecasts.

#### Clustering:
Clustering is an unsupervised learning algorithm used to group similar data points together based on their intrinsic characteristics or properties. The goal is to partition the data into distinct groups or clusters, where data points within the same cluster are more similar to each other than to those in other clusters. Clustering algorithms do not require labeled data and operate solely on the input features. Clustering is commonly used for tasks such as customer segmentation, image segmentation, and anomaly detection.

#### KMeans Clustering:
KMeans clustering is a popular clustering algorithm used to partition a dataset into K distinct clusters. The algorithm begins by randomly initializing K cluster centroids, then iteratively assigns each data point to the nearest centroid and updates the centroids based on the mean of the data points assigned to each cluster. This process continues until convergence, where the centroids no longer change significantly or a specified number of iterations is reached. KMeans clustering aims to minimize the within-cluster sum of squared distances, effectively grouping data points into clusters with minimal variance within each cluster. It is widely used for tasks such as customer segmentation, image compression, and document clustering.

## Usage

The models are implemented in the standard Jupyter Notebooks. To execute the notebooks, run each cell of the jupyter notebook in the top-down order (You can use `shift + enter` to execute the cells). The datasets are located in the `datasets` folder. The linear regression and clustering uses California Housing dataset, and Iris dataset respectievely.

## Getting involved

You may contribute to this library by adding Jupyter notebooks that teaches a machine learning topic, and contains exercises to practice. You may also choose to improve the existing notebooks. `develop` branch is where you will submit the PR to, which will then be reviewed and merged. Your changes should be submitted via a topic branch for which a meaningful name must be provided and the details of the PR should be included. The changes will be reviewed and merged to `develop` first and then to `master` branch.

## Future roadmap

The short term roadmap includes, but not limited to:
* adding notebooks containing distinct Machine learning topics
* arranging the topics by folders with appropriate documentation
* cleaning up unused or redundant files/folders
* new datasets and analysis for the same

## License

This project is licensed under the terms of the [MIT License](https://dougneiner.mit-license.org)
