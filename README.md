# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: Using bulleted lists and images to support your answers, address the following questions.

# Data Preprocessing

* What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL

* What variable(s) are considered to be the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

* What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME

# Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

I selected two hidden layers with 80 and 30 neurons. The input data has 43 features and 25,724 samples. Output layer is a binary classification. I used activation function ReLU and binary classification Sigmoid.

* Were you able to achieve the target model performance?

I was not able to achieve target model performance of 75%.

* What steps did you take to try and increase model performance?

I tried to increase model performance by adding neurons to one of the hidden layers, adding a hidden layer, and using a different activation function but was still not able to increase perfomance by a significant enough percentage.

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

With all the attempts, the model did not reach 75%. The closest we got was 72.9% with an added hidden layer. Another possibility would be to try using multiple decision trees combined to generate an output and evaluate the performance against the deep learning model.