# Statoil-Machine-Learning-Code
The Kaggle Statoil competition was a coding competition on kaggle.com in which participants were asked to automate the task of taking 2 bands of radar backscatter images from a satellite and classifying the object whose image was taken. There were two classes, iceberg and ship. The purpose of this was to decrease the costs of maintaining safe navigation in areas such as offshore of the east coast of Canada.

## Load_data.ipynb
I load the data from the files found here: https://www.kaggle.com/c/statoil-iceberg-classifier-challenge/data
I convert the data into numpy arrays, perform some visualization to understand the task
Then I store the data into a pickle file for later use.

## Basic Classifiers and NNs.ipynb
Using the pickled data, I try various machine learning techniques such as logistic regression and various SVMs. I also try transforming the data in various ways to improve performance. Finally, I implement a deep neural network.

## Convolutional Networks.ipynb
Due to the fact that the data is two bands of image data, a convolutional network is a natural option. I implement various convolutional network architectures to try to find the most effective one.
