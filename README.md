# Deep-Learning-assignment-1
Assignment 1 of the course Deep Learning.

Brief description:

The assignment is focused on the practical aspect of Deep Learning in which we're required to build, train and evaluate a Neural Network model.
The neural network created in this solution use the Penguin dataset from Seaborn and aims at classifying the species of a penguin (Adelie, Gentoo, Chinstrap) by features as Bill lenght, Bill depth, Flipper lenght and body mass. 
We use SMOTE to create sythetic data as to resolve imbalanced training data on the target variable.
After this we shortly discuss the different setup options in regard to the layer structure, loss-functions, activations functions and gradient decent options before chosing our selected setup.
Lastly we create 5 different models; first modifying hyperparameters (epochs and learning rate) and later on moving on to modifying the layer-structure and activations functions of the Neural network.
Afterwards we evaluate the models based on precesion, accuracy, recall and F1-score. 

From our analysis it seems like the modifed layer-structure models perform better, having higher accuracy and F1-scores. 


--------------
Appendix:
In the appendix we've attached an attempt at creating a Batch Gradient Decent structure without succes.
