# Neural_Network_Charity_Analysis

## Overview
Alphabet Soup is a nonprofit philanthropic foundation that aids organizations who's focus is enviornmental protection. We are helping a programmer from Alphabet Soup to analyze the impact of each donation and the risk of potential recipients.
Through the use of machine learning and neural networks and the features in the provided dataset, we create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
The main dataset used is a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

## Results
### *Data Preprocessing*

* What variable(s) are considered the target(s) for your model?
* What variable(s) are considered to be the features for your model?
* What variable(s) are neither targets nor features, and should be removed from the input data?

### *Compiling, Training, and Evaluating the Model*

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* Were you able to achieve the target model performance?
* What steps did you take to try and increase model performance?

## Summary
Even with the addition of more hidden layer, the accuracy target of 75% percent was not attained by the deep learning neural network model. It could be recommended to try the Random Forest Classifier, a Supervised Machine Learning model. Using this method would be less likely to be prone to influence of outliers.
