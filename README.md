# Neural_Network_Charity_Analysis

## Project Overview
The purpose of this project was to determine the success of funding specific organizations. Alphabet Soup has collected data about the organizations that they have funded over the years, and if those organizations were successful in using that money effectively.

## Results
**Data Preprocessing**
* The IS_SUCCESSFUL variable is the the target for my model
* The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPEACIAL_CONSIDERATIONS, and ASK_AMT are the features for my model.
* The EIN and NAME columns are neither targets nor features, and were removed.

**Compiling, Training, and Evaluating the Model**
* I used five hidden layers, which all used the sigmoid activation function because the model is performing logistic regression. The layers had 256, 128, 64, 16, and 4 neurons. The output layer had one neuron and the sigmoid activation function. I ran the model with varying amounts of layers and neurons, and found this configuration resulted in the highest accuracy.
* Despite my optimization efforts, I was not able to achieve the target model performance.
* Initially, I added columns and adjusted the number of neurons from the original model. Then, I dropped the SPECIAL_CONSIDERATIONS and ASK_AMT columns from the features, which slightly increased the performance of the model. I also adjusted the bin sizes of the rare variables in the APPLICATION_TYPE and CLASSIFICATION columns. I tried using different activation functions, like ReLU and tanh, but sigmoid got the best results. I also increased the number of epochs in the training regimen.

## Summary

My model was able to predict the success of funded organizations with 72.5% accuracy. Despite my attempts to optimize the model, I was not able to achieve 75% accuracy. Therefore, I would recommend trying a logistic regression model for this binary classification. Logisitc regression models are used to determine the relationship between the features and target variables, so I believe it would be able to better predict the success of the funds than a Dense Neural Network.
