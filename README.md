# Unsupervised-learning-recommender-system-and-reinforcement-learning



- Unserpervised learning
  - Clustering 
  - Anomaly detection
- Recommender System


# Clustering. (unsupervised)
Clustering is a technique in machine learning and data analysis that involves together similar data points into clusters. 

# Applications.
- Grouping similar news
- Market segmentation
- DNA analysis
- Astronomical data analysis

# K-mean intuations
- This is a clustering algorithm in machine learning that is used to partition a set of data points into K clusters. 
- The goal of the algorithm is to minimize the sum of squared distance between each data point and the centroid of its assigned cluster.


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/0643f389-0876-42ea-a43d-24c47b6aa794" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/0e7a9fb4-904f-4171-b358-c587e25cb030" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/839cf3d4-ca05-46d4-9fc6-de92c6f00695" alt="Image">


# K-means algorithm

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/0e7277d6-d827-4824-8fdf-76ba4f5685f2" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/bbd04e73-0fe1-45e8-84e4-fd1418a6ce86" alt="Image">


K-means for clusters that are not well separated

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/4aa80353-9ca8-4012-9860-6ff186b53e41" alt="Image">


# Optimization objective
  <img src="https://github.com/Code-with-jaycee/Advanced-learnng-algorithm/assets/87891857/bdf7c01c-004e-4d43-9027-51ae4a007a88" alt="image">

<img src="https://github.com/Code-with-jaycee/Advanced-learnng-algorithm/assets/87891857/fe8d0aa0-28db-4eae-9dde-3cdc3872c2b6" alt="Image">

<img src="https://github.com/Code-with-jaycee/Advanced-learnng-algorithm/assets/87891857/64af7f9a-4ca2-4563-8473-e1b334322f50" alt="Image">


<img src="https://github.com/Code-with-jaycee/Advanced-learnng-algorithm/assets/87891857/26b5849d-9f4e-40dd-a212-74ab83b5a326" alt="Image">


# Initializing K-means
<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/52253c7f-7267-4ee7-9fb2-5bf4b7acb52b" alt="Image">


# Random initialization
<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/69068f06-22fc-4cca-9aff-151fd602aa94" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/8cf684cd-adc0-4309-a0f5-6715bb516ef0" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/3d36928d-e085-4653-bc40-276ffdd653fa" alt="Image">


# Choosing the number of clusters

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/5f54548d-33fc-4535-8489-41db6862b7f9" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/cbdf5015-f22d-445b-acf6-4e553d2542c5" alt="Image">


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/83697746-e2f6-46c2-bcbd-6eace4956fcf" alt="Image">


# Finding unusual Events

# Anomaly detection
<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/76dd9c4d-26e7-4fff-ac4c-f86a6f75ef59" alt="Image">

Density estimation: 
- This is a fundamental concept in Anomaly detection withing unsupervised learning. 
- It involves estimating the probability density function(PDF) or probability distribution of a dataset to understand the underlying patterns and structures. 
- It helps in distinguishing between normal and anomalous instance by quantifying the likelihood of observing a particular data point within the dataset.

<h2>Techniques</h2>
- Parametric methods
  - This assume a specific probability distribution, such as Gaussian (normal) distribution, and estimate its parameters from the data. 
  - Non-parametric methods, on the  other hand, make fewer assumptions about the underlying distribution and estimate the density directly from the data without assuming any specific form. 
- Non-parametric methods

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/e1c065b7-93be-428a-b20c-1f1d809fcbc4" alt="Image">

# Application of Anormaly detection. 

1. Intrusion Detection: By modeling the normal behaviour of network traffic, any deviations from the expected pattern can be identified as potential anomalies, indicating a possible intrusion or malicious activity.
2. Fraud detection: By modeling the normal behaviour of legitimate transactions, any unusual or unexpeted patterns can be flagged as potential fraud. This can be applied to credit card fraud detection, insuarance claims fraud, money laundering detection. 
3. Manufacturng Quility Control: Density estimation can be imployed to identify anomalies or defects in manufancturing processes. 
4. Healthcare Monitoring: By establishing normal ranges for vital signs, lab results or physiological measurements , any values that fall outside these ranges can be identified as potential anomalies, triggering further investigation or intervetions.
   

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/510a3fda-132a-40fe-b738-d0d09d3ae5f7" alt="Image">

# Gaussian (normal) distribution

- This is also known as the normal distribution or bell curve, it is a probability distribution that is widely used in statistics and probability theory. 
- The Gaussian distribution is characterized by its symmetrical bell-shaped curve, which is parametrized by two values: The mean (μ) and standard deviation (σ). 
- The mean represents the central tendency of the distribution , indicating the average  or expected value, while the standard deviation represents the dispersion or spread of the data points around the mean. 
- The probability density function (PDF) of the Gaussian distribution is given by the formula:

f(x) = (1 / σ√(2π)) * exp(-(x-μ)² / (2σ²))

In this formula, x represents the variable or data point, μ represents the mean, σ represents the standard deviation, π represents the mathematical constant pi (approximately 3.14159), and exp() represents the exponential function.





<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/8e0d06ea-8d1a-4f94-b18e-57d3d9b73e74" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/eb69178e-85ac-4dec-9e36-abef8f6f9174" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/dde72d00-27d8-4a96-9514-57cd00131dc7" alt="Image">



# Anomaly detection algorithm
<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/f2133a52-8f06-4ae7-b344-11a253f23476" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/67d42aa3-1133-4d55-b3c9-7d31cff3ecf4" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/c064ae0f-c2b6-466c-950f-b33abf5ef4e8" alt="Image">



# The importance of real-number evaluation
<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/2b358f17-7b88-4548-982f-6d24bad2ffc7" alt="Image">


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/58100937-9c07-4b11-9a07-e084f3cee74e" alt="Image">


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/602025f4-c31d-4eab-95f2-9eae92ef72f0" alt="Image">