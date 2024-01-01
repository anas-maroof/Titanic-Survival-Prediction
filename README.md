# Titanic-Survival-Prediction
The Titanic Survival Problem is a well-known data science challenge that involves predicting which passengers aboard the Titanic survived the ship's sinking in 1912. The goal of the problem is to build a model that can accurately predict whether a given passenger would have survived based on a number of features, such as their age, gender, and passenger class. 

In this project more than modelling we will emphasize on the EDA part. We will be creating the ML models. We’ll use different algorithms and find the algorithm with the best accuracy. 
# ML Model
Now coming to the modelling part of the project. We will be using different machine learning algorithms to predict the survival of a person. 

Pre-processing the data before applying machine learning algorithms is an important step that can help improve the performance of your model. Some additional details about common pre-processing techniques include:

Handling missing values: NULL or missing values in your dataset can cause problems when training machine learning models, as many algorithms are unable to handle NULL values. There are several approaches you can take to deal with missing values, such as dropping rows or columns with missing values, imputing missing values with the mean or median of the feature, or predicting missing values using a separate model. Which approach you choose will depend on the specific characteristics of your dataset and the goals of your analysis.
Feature selection: Identifying the most relevant features in your dataset and selecting a subset to use in your model can help reduce the complexity of the model and improve its performance. There are several approaches you can take to select features, such as using statistical tests to identify the most important features, using domain knowledge to identify relevant features, or using machine learning algorithms that have built-in feature selection methods.
Feature engineering: Creating new features from existing features in your dataset can help capture additional information or trends in the data that might not be apparent in the raw features. This can be done through techniques such as combining or transforming existing features, or using domain knowledge to create features based on your understanding of the problem.
After Preprocessing the data, we can move on to splitting it into a training set and a test set. This is an important step because it allows us to evaluate the performance of your model on unseen data, which is a more realistic representation of how the model will perform in practice.

After splitting the data, it is often a good idea to perform feature scaling. This is a technique that adjusts the values of numeric features so that they have a common scale. This is important because many machine learning algorithms assume that the features are in the same scale, and failing to perform feature scaling can lead to poor model performance.

Once the data is ready, we can then apply a variety of machine learning algorithms to it and compare their performance. There are many different algorithms to choose from, and the specific algorithm that works best will depend on the nature of the data and the prediction task. Some common algorithms for the Titanic Survival Problem include:

Logistic Regression
Decision Trees
Random Forests
Support Vector Machines
K-Nearest Neighbors
After training and evaluating each algorithm, we can then compare their performance to see which one provides the most accurate predictions. To do this, we can use metrics like accuracy. These metrics will give you an idea of how well the model is able to correctly predict the survival of passengers. 
