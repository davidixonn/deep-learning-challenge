# deep-learning-challenge
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Steps
1. Preprocess data
2. Compile, train and evaluate the model
3. Optimize the model

## Report on Neural Network Model

### Overview
The purpose of the analysis is to predict which applicants will be successful with funding from the nonprofit foundation Alphabet Soup. A dataset is utilized to make a binary classifier along with machine learning and neural network.

### Results
#### Data Preprocessing
- What variable(s) are the target(s) for your model?
- "IS_SUCCESSFUL"
- What variable(s) are the features for your model?
- "NAME", "APPLICATION", "TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT","SPECIAL_CONSIDERATIONS", "STATUS", "ASK_AMT"
- What variable(s) should be removed from the input data because they are neither targets nor features?
- "EIN"
#### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The accuracy increased with three layers with many neurons and with the 2nd and 3rd activation (sigmoid). 
- 1st activation: relu, 2nd and 3rd activation: sigmoid
- Were you able to achieve the target model performance?
- We were able to achive target model performance.
- What steps did you take in your attempts to increase model performance?
- A 3rd layer, changing NAME to data points and going with the sigmoid activation function.

### Summary
Through the process of optimization, we were able to increase the accuracy. The optimized accuracy returned at approximately 78%. Steps taken to increase to this level was through having the name occur more than 5 times, application having either T3, T4, T5, T6, T7, T8, T10 and T19 and classification as C1000, C2000, C3000, C1200 and C2100.

Recommendation: Random Forest Model
Random forest can be used on both regression tasks (predict continuous outputs, such as price) or classification tasks (predict categorical or discrete outputs) which would be applicable in this instance.
