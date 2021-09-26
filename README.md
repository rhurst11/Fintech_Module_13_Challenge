# Fintech_Module_13_Challenge

## Purpose:

In this project, I attempt to optimize a neural network for a binary classification problem related to start up success. 

The model should be used as a filter for funding applications that make their way to various VC firms or incubators. If the model predicts start up success, that particular company may be be a good investment decision. 

## Approach:

My original model attained a decent level of accuracy and a bearable loss rate, but I made sure to test alternative models, eight to be exact. I changed layer number, neuron number throughout each hidden layer, activation function, and the number of epochs used to train the models. 

Somewhat frustratingly, my orignal model turned out to be the best option for both accuracy and minimzation of loss. 

The closest competitor for model performance is Alternative model 7. For alternative model 7, I used a similar structure and the same activation functions as the orignal model, but increased epoch size to 300 and added an additional hidden layer. The results were still slightly less optimized than my original attempt.

## Results:

The original model provides the most utility for predicting start up success out of the eight models evaluated in this project. This certainly should not preclude further optimization attempts, but should instead be used as a benchmark for any additional model creation. 