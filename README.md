# Machine_Learning_And_Statistics 

By Trish O'Grady

## How to use this Repository

Step 1. Install Anaconda


## What is Supervised Learning?


Supervised learning is a type of machine Learning that uses labeled training data to teach an algorithm how to make predictions on its own. Because it comprises a training phase where the algorithm is given a dataset that contains both input data and the appropriate output  or target values, it is known as a "supervised" learning method. The algorithm then learns by generalizing from the training data how to translate the input data to the desired output.
There are two types of supervised learning. One type is classification whereby the objective of classification issues is to assign input data to one of a number of predefined classes or labels. For example each of the three flower classes in the iris dataset—Versicolor, Setosa, and Virginica—has four features: sepal length, sepal width, petal length, and petal width. The classification of iris flowers aims to predict flowers based on their distinctive characteristics. The second type is Regression whereby regression problems are used to predict a numerical value or quantity based on the input data, which can be utilized for tasks like predicting the value of a house based on variables like location, semi-detached, private garden and so forth.
https://data-flair.training/blogs/iris-flower-classification/

https://www.geeksforgeeks.org/regression-classification-supervised-machine-learning/

The key components to supervised learning are as follows:
Input Data or Feautures. These are the parameters or variables that define the input. In a classification problem, these could be for example the measurements of an object. These might be variables influencing a numerical result in a regression problem.
Output data or Labels. The output data from supervised learning represents the predictions that the algorithm is attempting to make. Labeled data refers to training data that has already been associated with the desired result. For instance, the output in a classification problem might be a category label, while in a regression problem might be a number. 
Training Data: The input-output pairs make up the training dataset. It is applied to the machine learning model's training. This information is used by the algorithm to discover patterns and connections between the features of the input and the related output.
Model Learning: The machine learning model learns the fundamental patterns, relationships, and rules that map input data to output data using the training data. The objective is to develop a model that generalizes well and makes precise assumptions about new data.
Prediction: The model takes the input data, analyses it, and generates a prediction or conclusion as an output. Once the model has been trained, it may be used to make predictions on new data.
Supervised learning is a fundamental and effective machine learning approach that serves as the foundation for numerous practical applications.
https://www.sciencedirect.com/topics/computer-science/supervised-learning

# What are classification alogorithms? 
Machine learning applications use classification algorithms, a subset of supervised learning algorithms, to divide data into discrete classes or categories based on input features. These algorithms are made to recognize and learn from data patterns, which may then be used to categorize data points into predetermined groups.
Logistic regression is employed for binary classification issues when there are only two possible classifications for the output. The logistic function is used to model the likelihood that an input belongs to a given class.
In order to make judgments, decision trees iteratively divide the data into subsets according to the most important attribute. Both binary and multi-class classification can be done using them.
Multiple decision trees are combined in Random Forest, an ensemble learning technique, to increase accuracy and decrease overfitting. It works well for tasks involving classification and regression.
The kind of problem, the type of data, and the specific criteria all influence the choice of classification algorithm. It's normal practice to test out various algorithms to see which one does the task most effectively.

https://scikit-learn.org/stable/auto_examples/classification/index.html
https://www.datacamp.com/blog/classification-machine-learning

## An overview of the scikit-learn Python library

Scikit-Learn is a free machine learning library for Python. It provides tools for data analysis and modelling. It offers a variety of methods for classification, regression, clustering, and dimensionality reduction and supports both supervised and unsupervised machine learning.

Giving an input a label or category based on its features or qualities is the basic function of classification in machine learning.
Scikit-learn handles classification in a number of ways. Some algorithms include Random Forests and Decision Trees. These are helpful for classification and regression issues. K-Nearest Neighbour (KNN) is a straighforward yet powerful instance based categorisation technique.

Before choosing an algorithm for classification, data needs to be prepared and labelled so it is classified. After choosing a suitable algorithm like Random Forest or Nearest Neighbour, the model needs to be trained so it can find patterns within the dataset. Metrics then need to be applied to evaluate the performance. Once the model is trained it can be used to make predictions.

Like classification, regression is a supervised machine learning task that aims to predict a continuous numeric output variable using input information. It is used for estimating values, or modelling relationships between variables. It too needs prepared data before choosing an algorithm. The model is also trained and metrics are applied before making predictions.

In conclusion, scikit-learn is a flexible and popular Python framework for data analysis and machine learning. It is a crucial component of the toolset for data scientists and machine learning practitioners since it offers a complete set of tools for developing, assessing, and deploying machine learning models.

# A classification algorithm thats implemented using scikit-learn Python


https://scikit-learn.org/stable/index.html