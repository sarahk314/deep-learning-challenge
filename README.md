# Overview #
====================

The purpose of this analysis is to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.



# Results #
==================


## Data Processing ##
-----------------------------

* What variable(s) are the target(s) for your model?

    The target variable(s) for the model is `IS_SUCCESSFUL`

* What variable(s) are the features for your model?

    The feature variables for the model are all the other columns in the DataFrame, excluding `IS_SUCCESSFUL`

* What variable(s) should be removed from the input data because they are neither targets nor features?

    I removed `EIN` and `NAME` from the input data as they was neither targets nor features.


## Compiling, Training, and Evaluating the Model ##
-----------------------------------------------------------------

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

    For my final neural network model, I selected 3 layers with 50, 20, and 5 neurons respectively.
    
* Were you able to achieve the target model performance?

    No, I was not able to achieve the 75% target model performance.
    
* What steps did you take in your attempts to increase model performance?

    I tried a variations of changing the number of neurons in each layer, adding more layers, and using different activation functions for each hidden layer. However, in my various attempts, I was still not able to achieve 75% accuracy.



# Summary #
=====================

In my last optimization attempt, I was able to raise the accuracy up to 72.9%, but still did not achieve the goal of 75%. A different combination of changes, such as: trying out various activation functions, adjusting the number of layers and neurons, or changing the activation functions for each layer could ultimately contribute to optimizing the model and achieving the desired goal of 75% accuracy. 

A different type of model, such as a Random Forest Classifier, might be a better option for this type of classification problem to reduce the number of optimization attempts.