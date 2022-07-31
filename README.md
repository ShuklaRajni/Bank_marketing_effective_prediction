# Bank_marketing_effective_prediction

# Objective:
Predicting the effectiveness of bank marketing campaigns.

# Problem Statement:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.The classification goal is to predict if the client will subscribe a term deposit (variable ‘y’).

# Data Summary:

We were provided with following dataset:

Bank Client data:

● age (numeric) job : type of job

● marital : marital status

● education

● default: has credit in default?

● housing: has a housing loan?

● loan: has a personal loan?

Related with the last contact of the current campaign:

● contact: contact communication type

● month: last contact month of year

● day_of_week: last contact day of the week

● duration: last contact duration, in seconds (numeric).

Other attributes:

● campaign: number of contacts performed during this campaign

● pdays: number of days that passed by after the client was last contacted from
a previous campaign previous: number of contacts performed before this
campaign

● poutcome: outcome of the previous marketing campaign

Output variable (desired target):

y - has the client subscribed to a term deposit? (binary: 'yes','no')

# Introduction:

With the startling rise over the last few decades of media and technology which
increases the amount of information we have at our fingertips (cell phones,
television, Internet, etc.), humans are now more connected than ever. Marketing is
the most common method which many companies are using to sell their products,
services and reach out to potential customers to increase their sales.Telemarketing
is one of the most useful ways of doing marketing for increasing business and
building good relationships with customers to get business for a company.

# Classification Approach:

After understanding the problem statement, we loaded the dataset for following
operations:

● Data Exploration

● Exploratory Data Analysis

● Feature selection

● Balancing Target Feature

● Building Model

● Hyperparameter Tuning

# Handling Imbalance data Using SMOTE

SMOTE library used to generate synthetic data for handling the imbalance in the dataset

# Model building:

In this project we used the following models for classification Algorithms.

1. Logistic Regression

2. K-Nearest Neighbor
 
3. XGBoost Classifier
 
4. Random Forest

5. Decision Tree


