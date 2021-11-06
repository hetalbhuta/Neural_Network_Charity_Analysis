# Neural_Network_Charity_Analysis

Preprocessing Data for a Neural Network model and optimizing it

## Overview of the analysis:

Using my knowledge from machine learning and neural networks for this project I use the features in this dataset I create a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as organization type, the use of funding amongst others. This project is comprised of 3 steps: Preprocessing the data for the neural network, Compile,train and evaluate the model & finally optimizing the model.

## Results:

### Data Preprocessing
variable(s) that are considered the target(s) for your model?

* The variable we are targeting in this module is the IS_SUCCESSFUL column.
variable(s) that are considered to be the features for your model

* The features that we are using are every column except the ones that we will drop.
What variable(s) are neither targets nor features were removed

* First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

## Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model?

* This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

![image](https://user-images.githubusercontent.com/86137857/140591110-9275cbf2-af76-4178-bd88-c2b4a68f7b3e.png)


### Was the model able to achieve the target model performance?

* Although we the target for the model was to be 75% or above, I was not able to reach the target.
What steps were taken to try and increase model performance?

* Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.

![image](https://user-images.githubusercontent.com/86137857/140591137-a5228c31-3b0a-4214-93a5-fd7a5717e72d.png)

# Summary:

The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming. Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.
