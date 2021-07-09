# Neural_Network_Charity_Analysis-
## Overview
The purpose of this repository is to analyze a sample set of charity donations using neual network and tensor flow. The sample data will be preprocessed and run through multiple different models to determine if an accuracy of 75% can be achieved.
## Results
The sample data set was first preprocessed by dropping EIN and NAME columns which would not be relavent to the neural network train and test. While the column IS_SUCCESSFUL was the target predictive result of the machine learning model. This column was defined as the y variable while the rest of the input columns were defined as the X.

The original neural network model was set with two hidden layers with densities of 80 and 30 respectively. The input data had 43 features and 25,724 samples.

To improve the accuracy of the neural network, increased density of hidden layers were experimented with. The first layer was increased to 150 and the second layer was increased to 100. Additionally adding a third layer was tested however the 75% accuracy target was not achieved. The activation model was changed from relu to tanh which seemed to yield better results but still did not achieve 75%
## Summary
Ultimately this model had average accuracy. It was not able to achieve greater than 75% accuracy when predicting charity success. Additional sample data may help to improve the model as well as increased inputs. However, this may induced an over fit in data which limits the applicability of the model. 