# Neural_Network_Charity_Analysis
# Overview
The purpose of this analysis is to generate predictions for where to make investments for companies supported by Alphabet Soup. The given data includes over 34,000 organizations and the goal of this repository is to predict which companies will be successful if funded so that the limited amount of funding can go to them. 

# Results
## Data Preprocessing
### What variable(s) are considered the target(s) for your model?
The target variable is the "Is Successful" variable since that is the target output. In the end, whether the organization is successful is the objective.
### What variable(s) are considered to be the features for your model?
All other variables asides from the EIN and Name variables are the features or input variables since they all impact the success of the organization. Name has no relation to success.
### What variable(s) are neither targets nor features, and should be removed from the input data?
The EID and Name variables should be removed from the input data since they do not affect success nor indicate success.

## Compiling, Training, and Evaluating the Model
### How many neurons, layers, and activation functions did you select for your neural network model, and why?
The input dimension of this data should be 44 which was determined by the length of the scaled features.
### Were you able to achieve the target model performance?
The accuracy of my model reached 73 percent. 
### What steps did you take to try and increase model performance?
I created two layers to increase model performance and that increased the accuracy by close to a percent.

# Summary
In conclusion, this model was 73 percent accurate in predicting which organizations will be successful. This is relatively high considering there are 34,000 total organizations. To generate a better model, more variables would be helpful. Since multiple variables were objects that were converted into boolean 1's and 0's, the data had no in betweens which added to the difficulty in creating an accurate model. 
