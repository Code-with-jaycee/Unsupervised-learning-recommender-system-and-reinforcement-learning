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



# Anomaly detection Vs. Supervised learning


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/d4646a04-509c-4d93-9034-947e1491ccd4" alt="Image">


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/a05f45ce-9c96-49e0-a501-7e3e4fd43f1a" alt="Image">



# Choosing what features to use

- Non-gaussian features : These refers to features that do not follow a Gaussian or normal distribution. 
- In a guassian distribution, also known as a bell curve or normal distribution, the data is symmetrically distributed around the mean, with most of the data concentrated near the mean and tapering off as it moves away from the mean.
- Non-Gaussian features can have various types of distributions, such as skewed, multimodal, or heavy-tailed distributions. 

# Dealing with non-Gaussian features. 
1. Transformation: Applying mathematical transformation such as logarithmic, exponential, or power transformations to the features can help make the distributions closer to Gaussian. 
2. Non-parametric methods: Non-parametric methods, such as decision trees or support vector machines can be used when the underlying distribution of the data is uknown or does not follow a specific parametric form.
3. Feature engineering: Creating new features by combining or tranforming the existing features in a way that captures the underlying patterns of the data can sometimes make it easier for models to capture the non-Gaussian relationships.
4. Robust estimators: Using robust statistical estimators that are less affected by outliers can help mitigate the impact of heavy-tailed distribution.


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/d636dc21-cb01-4403-9679-1bf224d523a4" alt="Image">


# Error analysis for anomaly detection
- This refers to the process of anlysing and understanding the errors or discrepancies mande by anomaly detection model. 
- Anomaly detection aims to identify patterns or instances in data that deciates significantly from expected normal behaviour.
- Error analysis helps to assess the performance of the model, identify the types of erros it makes , and gain insights into the strengths and limitations of the model. 


<h3>Key Steps involved in error analysis.</h3>

1. Data collection and labeling: Collect a labeled dataset that contains both normal and anomalous instances. 
   - These labels indicate whether each instance is normal or anomolous.
   - This labeled dataset serves as the ground truth for error analysis.
2. Model training and evaluation: Train an anomaly detection model using a suitable algorithm or technique.
   - Evaluate the model's performance on separate validation or test dataset usign appropriate evaluation metrics such precision, recall, f1-score, or area under the receiver operating characteristics curve (AUC-ROC)
3. Error identification: Analyze the model's predictions on the validation or test dataset and identify instance where the model made errors.
   - Classify the errors into different categories, such as false positives (normal instances misclassified as anomolous) and false negatives (anomolous instances misclassified as normal)
4. Error characterization: Examine the characteristics of the errors to gain insights into the model's behaviour. 
5. Error Visualization: Visualize the missclassified instances or their representation to get a betther understanding of the errors. 
6. Error mitigation: Based on the insignts gained from the error analysis, refine or improve the anomaly detection model.
7. Iterative process: Error analysis is an iterative process that involves repeatedly training, evaluating, and analyzing the model's performance.



<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/3e2f2afe-e294-491c-8e33-80b206260431" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/ac44c3db-8ce0-485d-941c-1fc218515d95" alt="Image">


# Recommender system

 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/98a09f65-c127-4cbf-b9d0-7934e7491236" alt="Image">


 # Collaborative Filtering
 Using per-item features

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/9b29df95-0c21-4ecf-bb2b-c6ec01a91699" alt="Image">

# Cost function(objective function or loss function)

- This is a measure of how well a machine learning model performs on a given dataset.
- The cost function quantifies the difference between the predicted output of the model and the actual output, which is known as the ground truth or target value.


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/0dec6bb1-109e-4b11-8fc1-b1a7536f1dc3" alt="Image">


# Collaborative filtering algorithm

 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/e59d5a45-6b92-46cb-800c-9329afc422f8" alt="Image">


 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/4c313f01-2850-4fe3-bac1-220b38ec5f52" alt="Image">

 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/040c5c69-7680-4535-aa31-77f3764201de" alt="Image">


 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/bfaef4d2-d165-4ee0-b00d-5895efb93802" alt="Image">


 # Binary labels: Favs , likes and clicks
 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/2fd316a0-a99e-4618-a768-35e65cbbf925" alt="Image">


 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/e4a6d6bd-1844-45d4-b7eb-f8c024d09a1a" alt="Image">


 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/cef6ab94-14f5-4044-a3e6-8904d9d951b4" alt="Image">

 <img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/3b5b05fc-0c36-488d-b03f-0f11fe4b51e4" alt="Image">


# Mean normalization

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/41f41f90-3eaf-4e55-bf56-09a6284fc1b1" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/575f85b3-d8fe-40c9-86fa-11036450c991" alt="Image">


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/c01a570d-9599-4a5b-8e29-1fafec51f79f" alt="Image">

# Tensorflow Implementation
<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/1e1ef524-481f-4b63-bf52-a1c6a0fd5fa4" alt="Image">


# AUTO DIFF (Automatic differentiation)

- This is a technique commonly used in machine learning and optimization algorihms.
- It is mathematical tool that allows the efficient and accurate computations of derivatives, which is essential for training machine learning models. 
- In machine learning, models are trained by optimizing their parameters to minimize a loss function. 
- This optimization process often involves calculating the gradient of the loss function with respect to the model parameters.
- Machine learning frameworks , such as TensorFlow and PyTorch, provide automatic differentation functionality as a core feature. 
- This allows developers to define their models and loss functions using high-level abstractions and perform efficient gradient computations for training the models.

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/288c1178-caf0-4517-b333-a85e713d05a1" alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/3c757fb3-4c37-4915-8d74-17d3f9a106b1" alt="Image">


# Finding related items.(Collaborative Filtering)

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/28fca7fb-291b-421a-bd62-7da69329e4c7" alt="Image">


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/30dfd295-fea1-4631-ad24-452a19371f33" alt="Image">


# Collaborative filtering Vs Content-based filtering.

- Collaborative filtering: This focuses on analyzing user behaviour, preferences, and patterns of interation to make recommendations. 
- It assumes that users with similar interests in the past will have similar preferences in the future. 
- It can be devided into
  
  - User-Based Collaboration Filtering : This approach recommends items to a user based on the interests and behaviours of other users who are similar to them. 
  - It finds users with similar item preferences and recommends items that those similar users have liked or rated highly.

  - Item-Based Collaborative Filtering - The similarities between items is calculated based on the rating and preferences of the users.
  - Recommendations are then made based on the items that are similar to the ones the user has already liked or rated.

- Collaborative filtering does not require explicit knowledge about the items or users' attributes. 
- It relies solely on user behaviour and item ratings.
- One limitation of collaborative filtering is the cold start problem, where it struggles to make accurate recommendations for new users or items with limited data.
  

- Content-Based Filtering - This focuses on the characteristics or attributes of items being recommended.
- It uses features or attributes of the items themselves to find similarities and make recommendations.
- For example in movie recommendation system, the attributes could include genre, director, actors.

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/d97feeac-7d17-4393-9451-74185db3c602"
alt="Image">

<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/a1fb1643-a267-4ffe-a03a-9bb29d5db98b" alt="Image">

# Content-based filtering: Learning to match


<img src="https://github.com/Code-with-jaycee/Unsupervised-learning-recommender-system-and-reinforcement-learning/assets/87891857/c03e2e67-12ce-4bb8-81bd-558fdcd5037d" alt="Image">