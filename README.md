# Brand_Selection

## Data Overview:

The dataset contains the answers of the survey including the following variables (Salary, Age, Education Level, Car, Zipcode, Credit, Brand). 
The results of the survey were filled out by 10,000 of our existing customers.

## Data Pre-processing:

First step of the analysis was to pre-process the data (correcting types of variables, randomizing observations, cross validation). 

## Methods of Analysis:

The process continued by splitting the data into training-set and testing-set; which were used to build the model using the training-set, 
then applying it on the testing-set to see how much accurate is the model. 

The models which were used are based on 2 classifiers (Random Forest and C5.0 Decision Trees).

The results of applying our models showed that they have a similar pattern regarding the accuracy & kappa (higher agreement between 2 variables). 

Since the accuracy & kappa of the C5.0 model were slightly better than the ones in Random Forest, 
therefore, the analysis of prediction was made with the C5.0 model.

It is quite important to mention that during this analysis, it was shown that there was a correlation between customers’ salary and the brand. 
The higher the age of the customer, the more their preference is to buy Sony instead Acer “this could be affected by the better income with higher age”.
Adding to the previous notes, there is no significant correlation between the other variables and the brand.

## The Results:

Diving into the results of the prediction, it was clear that the customers did prefer Sony instead of Acer.
