# Aries_Ml_Project

The project aims to recommend travel areas to the users and help them plan their itinerary in the most efficient way as per their given timeline and preferences. 
The project uses Decision Tree Algorithm as a classifier in order to recommend travel areas to travelers. Model takes user input in form of tags, category and seasons and give the output relevant to it.Pre-processing techniques like: data cleaning, one-hot encoding have been used to eliminate empty,blank or repeated value from the dataset.After cleaning  and transforming the data, we’ve used decision Tree Classifier method library and Random Tree Classifier Method by importing Sklearn library  to predict the most accurate location.

Introduction

The project aims to recommend travel areas to the users and help them plan their itinerary in the most efficient way as per their given timeline and preferences. 
The project uses Decision Tree Algorithm as a classifier in order to recommend travel areas to travelers. When a new user enters a requirement the decision tree will predict the best and most accurate location. 
Pre-processing techniques like: data cleaning, one-hot encoding have been used to eliminate empty or wrong values from the dataset.
 After cleaning  and transforming the data, we’ve used decision Tree Classifier method library and Random Tree Classifier Method by importing Sklearn library  to predict the most accurate location.
LITERATURE REVIEW

One hot encoding: We’ve used one hot encoding on categorical features like:tag, category and seasons 
Feature Selection based on correlation:
Data Visualization: We’ve plotted scatter plots using MatplotLib
Categories: These include:- friends, family and couple
Tags: These include:- historical, pilrimage, beaches, mountains, waterfalls, adventure, trekking, cultural.
Seasons: These include:- winters, summer, spring
Places: These are the target variable which will by recommended by the model.
METHODOLOGY

Pre-processing techniques: 
Data Cleaning: We performed data cleaning on the dataset which is a very important step before working on any model. It enable the cleaning of any inappropriate data or missing values in the dataset.

One hot encoding: Our dataset comprised of categorical data: categorical tags:- historical, pilgrimage, beaches, etc., seasons, age group, category like: family, friends, solo, couple.

Decision Tree Classifier Algorithm:

       The model is trained using Decision Tree Classifier Algorithm, since the main aim of the model is to perform classification of the places based on categories like whether it is historical, pilgrimage, beaches, mountains, age group that would prefer a particular location, seasons preferable for a place, and what kind of group to go with. Hene , we went further with this algorithm.

Random Forest Classifier Algorithm: 

We also tested our data on Random Forest Algorithm. It provided a higher level of accuracy in predicting outcomes over the decision tree algorithm hence producing good predictions.



Data Visualizion:

We’ve plotted”scatter plots”  and “bar graphys” by importing “matplotlib” of python in order to get a visual form of data.
Accuracy comparison of Models:

Scatter plot: place vs Tag

EXPERIMENTS/ SIMULATIONS

Appropriate dataset: We started with a dataset webscarapped from www.holidify.in. We got a number of errors while webscrapping. Also, the dataset produced wasn’t appropriate for the project as decision tree couldn’t be applied on it. Therefore we’ve generated a new dataset on which “Decision tree Classifier Algorithm” could function well.
Data cleaning and Data Preprocessing: We performed data cleaning to remove the inappropriate and missing features.
We implemented several preprocessing techniques like:  feature selection based on correlation to increase the accuracy but it showed 0 accuracy probably because of less data.



We aim to take user input in form of tags, category and seasons.
We played around with the decision tree classification and random forest classification for predicting the most accurate place.
The project helped us explore number of techniques and libraries. 
We tried to deploy the model using FLASK framework of Python but failed to do so because of lack of time.
RESULTS
Decision Tree Classifier results: 

Score:

Accuracy:

Random Forest Classifier results:

Score:


Accuracy:

User input:


Output based on Decision Tree Classification:


