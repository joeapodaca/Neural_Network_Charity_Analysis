# Neural_Network_Charity_Analysis

## Overview
Use your knowledge of machine learning and neural networks to help the foundation predict where to make investments.  Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


## Results

### Preprocessing Data for a Neural Network Model
What variable(s) are considered the target(s) for your model?

IS_SUCCESSFUL was used as the target.

![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/target.JPG)

What variable(s) are considered to be the features for your model?

application_cat is the features used in the model.

What variable(s) are neither targets nor features, and should be removed from the input data?

EIN and NAME are neither targets nor features and can be dropped from the data.
 
![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/drop.JPG)

### Compile, Train, and Evaluate the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Trained with 2 layers using the relu activation for each layer.

![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/define_model.JPG)

### Optimize the Model

Were you able to achieve the target model performance?

All changes to optimized had little affect on the performance.

What steps did you take to try and increase model performance?

Tried to optimize with 3 layers still using the relu activation for each layer.

![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/three_layers.JPG)

# Summary
The first attempt was the most accurate.  Most changes resulted in only a slight change in the accuracy.

