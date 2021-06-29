# Neural_Network_Charity_Analysis

## Overview of the analysis: 
Using the features in the provided dataset I helped Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 
### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  - IS_SUCCESSFUL
- What variable(s) are considered to be the features for your model?
  - EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL
- What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN, NAME 
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - The original model ran with 43 input features with two hidden layers consisting of 80 neurons and 30 neurons
- Were you able to achieve the target model performance?
  - No, I was unable to reach the target. I was able to increase the accuracy to 73%, but not the requested 75%.
- What steps did you take to try and increase model performance?
  - To try and optimize the model, I attempted to make 3 changes, including: changing the activation from relu to tanh, changing the neurons for each hidden layer, and also added     an additional layer.

## Summary: 
In summary it seems that we don't have enough information in order for a more accurate model. A few key features that I would recommend be added which are likely to increase the accuracy could be as simple as obtaining additional information pertaining to the use or distribution of funds or even dates showing when funding was provided and requested. 
