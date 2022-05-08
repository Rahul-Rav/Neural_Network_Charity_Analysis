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
'IS_SUCCESSFUL' is considered to be the target for this model

* What variable(s) are considered to be the features for your model?
'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', and 'SPECIAL_CONSIDERATIONS' are considered to be the features for this model

* What variable(s) are neither targets nor features, and should be removed from the input data?
'EIN' and 'Name' are neither targets nor features, and were removed from the input data.

![Screen Shot 2022-05-08 at 5 39 42 PM](https://user-images.githubusercontent.com/95504135/167316900-b9f072b5-536b-413b-8c88-51bb7936bf89.png)


### *Compiling, Training, and Evaluating the Model*

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
There are two 'hidden_nodes_layer' variables and have 80 and 30 neurons and 'relu' and 'sigmoid' are the activation functions used for the hidden layers.

* Were you able to achieve the target model performance?
The target mode performance was aimed to be higher than 75% and was not achieved, resulting in a 72% accuracy.

![Screen Shot 2022-05-08 at 5 37 01 PM](https://user-images.githubusercontent.com/95504135/167316827-dc68eb66-6876-47be-9d24-57f149223ae3.png)

* What steps did you take to try and increase model performance?
Optimization through the addition of hidden layers in order to increase the model performance was attempted in Deliverable 3.

![Screen Shot 2022-05-08 at 5 38 34 PM](https://user-images.githubusercontent.com/95504135/167316856-4714b452-90c9-4e1f-a225-85ea7e664399.png)


## Summary
Even with the addition of more hidden layer, the accuracy target of 75% percent was not attained by the deep learning neural network model. It could be recommended to try the Random Forest Classifier, a Supervised Machine Learning model. Using this method would be less likely to be prone to influence of outliers.
