# Neural_Network_Charity_Analysis

## Overview
Use your knowledge of machine learning and neural networks to help the foundation predict where to make investments.  Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


## Results
Here are the results.

### Preprocessing Data for a Neural Network Model
Use the IS_SUCCESSFUL as the target.

![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/target.JPG)

 EIN and NAME are neither targets nor features and can be dropped from the data.
 
![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/drop.JPG)

### Compile, Train, and Evaluate the Model

Trained with 2 layers using the relu activation for each layer.

![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/define_model.JPG)

### Optimize the Model

Tried to optimize with 3 layers still using the relu activation for each layer.

![SMOTE_oversampling_report](https://github.com/joeapodaca/Neural_Network_Charity_Analysis/blob/main/three_layers.JPG)


# Summary
The first attempt was the most accurate.  Most changes resulted in only a slight change in the accuracy.

