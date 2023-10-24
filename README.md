# Which Portugese banking institution customers subscribe to term deposit?

I have used CRISP-DM model for analysis of the data,building a model, evaluating the model with cross validation.
The steps are below.

### Business Understanding
The paper explains nicely about the features and their usage for better analysis. It provides lotof information for looking at the data from different lens.
### Background:
Bank wants to know which customers will subscribe to term deposit.
### Business Objectives: 
Identify what are the features or attributes that drives the success or failure of term deposit.
### Business Success Criteria: 
Identify appropriately what features will drive the customers subscribe to term deposit, so that we can target those customers
### Access Situation: 
We need to identify the dataset that contains several features of the customers.
### Risks: 
There may be a possibility of the data is not accurate or insufficient or not useful
### Costs/Benefits: 
The cost to run analysis to give the which customers will subscribe term deposit, so that we can focus on our marketing efforts.
### Data Mining/Success goals: 
Identify data, collect the data elements, and samples for various sources. Here the data set is given.
### Project Plan: 
Prepare a project plan to collect data, resources, data analysis,  modelling, deployment and monitoring.
### Tools: 
Several classification algorithms, jupyter notebook

### Data Understanding
After reading the paper, that has gone thru collecting the data with CRISP-DM method, it gives the good idea on the features and importance, and helped to develop basic understanding of data

### Collect Initial Data:
Run several campaigns to collect the data. Here we got the dataset, so we are not doing anything.
### Describe Data:
The data has 41188 data points with 21 features with several data types.
### Explore Data: 
Explore the data with techniques to identify what features are important using several plots, detecting outliers, treat missing values,data type changes, data cleansing, and null checks etc.
### Verify Data Quality: 
Inspect the data for quality, consistency, range, and length etc.

## Data Preparation

### Data Cleaning:
Cleaned the data, checked for nulls,categorized the data of non-numeric columns using several encoding techniques.

Prepared correlation matrix for identifying the relationship between these variables

Built PCA components to see what are the main features and how it is impacting the customer behaviour

## Modelling & Evaluation

Used several techniques to build and comparing performance of algorithms

## Summary of Model Performance and Valdiation


                    Train Time	Train Accuracy	Test Accuracy
model			
K Nearest Neighbors	0.006158	0.952710	0.916633
Logistic Regression	0.119023	0.926934	0.925225
Decision Tree	0.162747	0.927874	0.924151
Support Vector Machines	5.965148	0.918342	0.918244

Next Steps:

Now that we have some basic models on the board, we want to try to improve these. Below, we list a few things to explore in this pursuit.

More feature engineering and exploration. I need to do more analysis on evaluating the feature importance, probably try several feature engineering techniques.
Hyperparameter tuning and grid search. I have used all the fit methods, need to expand to GridSearch where I can play with hyperparamters and other option tuning.
And then compare all of the different algortithms to see what works better with what data.



## Deployment
Now that we've settled on our models and findings, it is time to deliver the information to the client.

## Final Report:

It seems like SVM took more time to perform fit, and KNN has highest accuracy in both test and train, it is also a faster model.It seems like it is best to use KNN until we explore further on the hyperparameters.

It also seems that the customers with the below features are most likely to subscribe to term deposits than others.