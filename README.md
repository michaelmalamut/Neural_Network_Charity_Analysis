# Neural_Network_Charity_Analysis

## Overview of the analysis
Using Machine Learning and Neural Networks for this project, I used the features in the dataset to create a binary classifier that will help to predict if the applicants that will be funded by a Charitable organization called Alphabet Soup will be successful. For this analysis we had a dataset containing various measures on 34,000 organizations that have been funded by Alphabet Soup.

## Results
### Data Preprocessing

* Variable that was considered as the target for my model: IS_SUCCESSFUL Column
* Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
* Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome

### Compiling, Training, and Evaluating the Model

* Initial preparation for the Sequential Neural Network specified 43 input features, into three processing layers that began with 80 neurons and decreased to 30 and 15, and a single output layer.
* The target performance of 75% accuracy was not met (72.75%).
* Further testing was done with three dynamic tuned models that statically and dynamically selected inputs, layers, neurons, and activations. These attempts yeilded accuracy results of:
** First Model: 73.49%
** Second Model: 73.17%
** Third Model: 73.51%
* Although accuracy was only improved marginally, the total loss of the dynamic deep learning models did offer an excellent decrease in the Loss factor.
