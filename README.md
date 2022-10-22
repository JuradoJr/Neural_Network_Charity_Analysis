# Neural Network Charity Analysis

## Overview of the analysis: 

The purpose of this analysis was to use machine learning techniques and neural networks to help predict the success rate of applicants when they are funded by a charity organization.


# Results:  

## Data Preprocessing

### What variable(s) are considered the target(s) for your model?

The variable that is considered the target for the model is the “Is Successful” column.

### What variable(s) are considered to be the features for your model?

The variables that are considered features for the model are the following: Name, Application, Type, Classification, Affiliation, Use_case, Organization, Income_Amt, Special_consideration, Status, and Ask_amt.

### What variable(s) are neither targets nor features, and should be removed from the input data?

The variables that should be removed are the Employer Identification column due to unnecessary information and also the special consideration column due to there being too minimal of cases to its inability to be quantified. Some may even decide to drop the status column due to every single row having the same value.



## Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?

I selected the same amount of epochs and used the ReLu method on the first activation function, and used the sigmoid activation function for the second and third activation function.

### Were you able to achieve the target model performance?
Yes, I was able to reach the target model performance


### What steps did you take to try and increase model performance?
The steps that helped increase model performance were changing the activation function on a layer as well as editing some columns to be seen as data points.



# Summary:  
In conclusion, we were able to successfully classify data points with a high accuracy percentage. We also found that in order for an applicant to have the best success rates it is fundamental that they: apply 5+ times and have a C1000-3000 classification. The best model that worked out was the Random Forest model due to increasing the accuracy above the other methods previously used.
