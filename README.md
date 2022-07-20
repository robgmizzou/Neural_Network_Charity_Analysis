# Alphabet Soup Charity Analysis

## Overview
Alphabet Soup has tasked us with buiding a model to provide insight into organizations that are successful in deploying the donations received.  Our model will help analyse which organizations are better bets for placing Alphabet Soup's donations.  A sizable data set of thousands of organizations has been provided with 12 data points per organization for us to model.<br>

## Results
### Data Preprocessing
Due to the nature of some of the variables, binning and encoding were required.<br>
#### Target Variable
"IS_SUCCESSFUL" was provided and was the target variable for our analysis.<br>
#### Feature Variables
Application Type, Affiliation, Classification, Use Case, Organization, Status, Income Amount, Special Considerations and Ask Amount were all retained variables for the modeling.<br>
#### Removed Variables
EID and Name were identification variables that we dropped as they were neither targets or features.<br>
### Compiling, Training, and Evaluating
Eventually, many combinations of neurons, layers and activation functions were modeled, but the most successful models all topped out around 72%.  
-In the end, three hidden layers with 80, 60 and 30 nodes respectively are shown in the submitted model.  
-Activations for the hidden layers were relu functions, with a sigmoid used in the output layer.  
-Functionally, in working toward the model target of 75% accuracy, we added a hidden layer and increased neurons, but at a marginal gain over the initial challenge guidance.  Removal of certain feature variables was also attempted, but with insufficient success to meet the model target.

## Summary
Unfortunately, the iterations and adjustments to the model were unsuccessful in my attempts to meet the target model accuracy of 75%.  As this was a binary modeling exercise in identifying high risk organizations, a model distinguishing into 2 classes, separating high risk from more effective charities, could lead to a better outcome given the task at hand.
