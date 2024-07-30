# Module19_BranchedNeuralNetwork_HRChallenge

In this challenge we were tasked with creating a neural network clasiification and prediction model to predict whether employees are likely to leave the company as well as if an employee may be better suited to other departments. We created Functional API and softmax activation model using Tensorflow keras which gave 81.52% Attrition accuracy and 64.13% Department accuracy, based on the data (csv) provided by the company.

Authors & Citation

Shephali Dubey
ChatGPT
Timothy Heidcamp, Andrew Crawford, Alberto Aigner and Revati Kulkarni assisted with an error resolution


Summary

First you import libraries and dependencies, Next, load data from the csv file, then check the data type to ensure the data is numeric and not an object or a string. If its an object, in needs to be encoded using one hot encoder. Next, preprocess data , define the target datset as Y and choose 10+ Columns as X (i chose 12),  Split the data into training and testing set,  normalize the data by using StandardScaler for X data, One Hot encoder for Department and Attrition columns , create a neural network (by assigning an Input layer, 2 shared layers, 2 hidden layers and 2 output layers, as well as neurons/units in each layer). Use Tensorflow Keras Functional API model, Softmax activation, for creating the neural network model. Next, compile and fit the model using the categorical_crossentopy for Department output and binary_crossentropy for Attrition loss function, the adam optimizer, and the accuracy evaluation metric, and predict accuracy and loss scores.Review Accuracy scores to evaluate if accuracy metric was the best use for this data. Finally,certain recommendations have been made for improving the model.
