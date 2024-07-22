# deep-learning-challenge

### Overview of the Analysis
The goal of this project is to create a model that predicts whether applicants for funding from Alphabet Soup, a nonprofit organization, will be successful. Using historical data from past funding recipients, we aim to build a binary classification model to help Alphabet Soup identify the applicants most likely to succeed. This involves several steps: cleaning and preparing the data, building and training the model, and evaluating its performance to ensure it makes accurate predictions.

## RESULTS
-Target Variables:
'IS_SUCCESSFUL'

## Feature Variables:
'APPLICATION_TYPE'
'AFFILIATION'
'CLASSIFICATION'
'USE_CASE'
'ORGANIZATION'
'STATUS'
'INCOME_AMT'
'SPECIAL_CONSIDERATIONS'
'ASK_AMT'

## Removed Variables:
'EIN'
'NAME'

## TRAINING THE MODEL
Neurons, Layers, and Activation Functions:

1 Layer: 128 neurons, ReLU activation
2 Layer: 64 neurons, ReLU activation
Output Layer: 1 neuron, Sigmoid activation

## PERFORMANCE
The model achieved an accuracy of 0.7260 

## Steps Taken to Increase Model Performance
-Data Preprocessing: Removed irrelevant columns (EIN, NAME), replaced rare categorical values with "Other", and converted categorical variables to numeric using pd.get_dummies.
-Model Architecture: Experimented with different neurons, layers, and hyperparameters.
-Feature Scaling: Used StandardScaler for better convergence.

## Summary
The deep learning model developed for Alphabet Soup achieved an accuracy of xx% on the test data. With two hidden layers using ReLU activation and an output layer with Sigmoid activation, the model effectively captured patterns to predict successful funding outcomes.