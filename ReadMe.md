# Neural Network Analysis 

## Overview 

This purpose of this project is to use machine learning and neural networks to analyze different projects funded by Alphabet Soup. 

## Analysis 

We are using machine learning to predict the success rate of the loans funded by Alphabet Soup. Machine learning will allow us to predict the relative risk of the loan. 


### Data Preprocessing 
- The target variable in this analysis is IS_SUCCESSFUL 


- The features in this application are: APPLICATION_TYPE, AFFILIATION,CLASSIFICATION, USE_CASE, 
ORGANIZATION, STATUS, INCOME_AMT, 

- EIN and NAME are neither targets nor features and were removed from the imput data. 

### Compiling, Training, and Evaluating the Model 

- Two layers were initially selected for this analysis. A sigmoid layer with 100 neurons. A second relu unit was used with 100 neurons as well. In the optimization several more layers were added, though they didn't do much to improve the model. 
- I was not able to achieve peak data performance. I tried removing columns in attempt 1 - 3, and in attempts 4 and 5 I added hidden layers. My efforts did not help the model. Also, I was having issues with my machine while performing the analysis. When I was training the model, I kept getting back and error that numpy arrays were not supported. I tried repeatedly to resolve the problem by reinstalling components, and finally found that if I put X_train_scaled into a pandas dataframe it let me run the analysis. From the internet I read this may be the case because im using a M1 Mac. 
- I made 5 attempts to increase performance. I altered the number of neurons, added hidden layers, pulled columns, and changed the test used (Rulu, Sequential, etc.) Nothing helped my model improve its accuracy. I think it may have been because i was getting the error while trying to train the model. 

# Summary

In summary I was not successful in improving the results of the deep learning model. I however did believe I got the coding right, and wished it would have worked as intended. I spent a lot of time troubleshooting, ultimately unsuccessful. 

