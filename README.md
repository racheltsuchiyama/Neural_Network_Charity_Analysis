# Neural_Network_Charity_Analysis

## Project Overview
The purpose of this project was to determine the success of funding specific organizations. Alphabet Soup has collected data about the organizations that they have funded over the years, and if those organizations were successful in using that money effectively.

## Results
**Data Preprocessing**
* The IS_SUCCESSFUL variable is the the target for my model
* The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPEACIAL_CONSIDERATIONS, and ASK_AMT are the features for my model.
* The EIN and NAME columns are neither targets nor features, and were removed.

**Compiling, Training, and Evaluating the Model**
*
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?

## Summary


I would recommend trying a logistic regression model for this binary classification. Logisitc regression models are used to determine the relationship between the features and target variables, so I believe it would be able to better predict the success of the funds.
