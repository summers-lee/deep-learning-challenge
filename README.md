# deep-learning-challenge
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively


Overview 
Analysis is to use machine learning and to help find and select the best applicants to fund through our nonprofit. It is shown in the column IS_SUCCESSFUL if the received funding and this is the target variable. The non-relevant columns are EIN and names, while every other column is a feature variable. The feature variables show relevant information about the data and could be used to help predict the target variables, while non-relevant variables are dropped from the dataset to help avoid excess noise and confusion from the model.
Results
I set the input layer with 10 neurons, a second layer with 4 neurons I selected the relu activation function for the first and second layers, and the sigmoid activation function for the output layer since the goal was binary classification, I also trained the model with 100 epochs. I optimized my model by adding 2 dropout layers with a rate of 0.2 for generalization and had the activation function as relu in the input and hidden layer. No, I was not able to obtain the 75% accuracy rating. 
Summary 
Since I did not reach the goal of 75% accuracy, I can’t recommend my above model. If I were to be granted more time I would try different combinations of activation functions and adjust the numbers of layers and neurons to see if that would assist in optimizing the model to get the desired goal.

