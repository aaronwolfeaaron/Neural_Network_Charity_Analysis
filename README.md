# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis was to use a neural network machine learning model to identify a level of predictibility for success of charities funded through Alphabet Soup. 

## Results:
### Data Preprocessing
-What variable(s) are considered the target(s) for your model? The "IS_SUCCESSFUL" column
-What variable(s) are considered to be the features for your model? All other columns which are not dropped
-What variable(s) are neither targets nor features, and should be removed from the input data? The dropped columns "EIN" and "NAME"

### Compiling, Training, and Evaluating the Model
-How many neurons, layers, and activation functions did you select for your neural network model, and why? 2 hidden layers: one with 80 neurons, the other with 30. Relu was used as the function for the hidden layers and sigmoid was used for the output layer.
-Were you able to achieve the target model performance? No, the highest model performance I was able to achieve through three attempts was 66.2%.
-What steps did you take to try and increase model performance? I removed columns, increased number of neurons, and changed activation function.

## Summary
Because I was unable to optimize the model to >75%, I don't believe it was effective in accomplishing my goal of identifying successful charities through machine learning with neural networks. In future assessments, I would further hone the data by dropping more columns that didn't lend to more predictible outcomes. 
