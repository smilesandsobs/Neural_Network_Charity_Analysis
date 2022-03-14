# Neural_Network_Charity_Analysis

## Overview of analysis: purpose of this analysis.

Alphabet Soup is a philanthropic foundation dedicated to helping organizations which help the environment, improve peoples wellbeing and unify the world. They have raised and donated over $10 billion dollars over the last 20 years. 

Our goal is to analyse the impact of each donation and vet potential recipients. To see which organizations are worth donating to and which are not a good option. This is to make sure that donations that the foundation make are impactful. 

To do this we are designing a deep learning neural network which can accurately make these predictions.

## Resources:

-Data Souce: charity_data.csv

-Software: Python 3.7.12, Jupyter Notebook

## Results:

### Data Preprocessing:
#### What variable(s) are considered the target(s) for your model? What variable(s) are considered to be the features?

The variable which was the target for this analysis was the IS_SUCCESSFUL column of the charity_data.csv. The other columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, were the features. 

#### What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME were dropped from the dataset and were neither targets nor features for this analysis. 

### Compiling, Training, and Evaluating the Model

#### Were you able to achieve the target model performance?

I was unable to achieve the target model performance. 

#### What steps did you take to try and increase model performance?

To increase the target model performance I attempted to create a callback that saves the model's weights every 5 epochs, I increased the number of layers from 2 to 3 and increaseed the number of neurons, I played with the optimizers for each layer, I tried increasing the number of epochs and I changed the model's weights so that they were saved every 5 epochs.

## Summary:

I was unable to increase the accuracy score of the model. Additional work could be done to optimize this model with more attemps, or a new model could be made using Random Forest classifiers.
