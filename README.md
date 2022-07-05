# CERN-Proton-Collision-Dataset-Prediction-of-Jet-Numbers
The CERN Proton Collision Dataset is used to predict the number of Jets in an event with an accuracy of 92% using TensorFlow.
My goal is to share my experience and codes with others, and I hope they find them useful.
The highest accuracy range of this problem in Kaggle was 82%, and I improved it by 10%.
The first thing I do is train two simple Neural Networks(Model 1 & Model 2), and then plot accuracy and loss graphs on the training and validation datasets to find a balance between the model that is underfitting and one that is overfitting(or converging), resulting in a model with a good fit.

According to my findings, based on the number of hidden layers and neurons and their activation functions, Model 1 with 89% accuracy and Model 2 with 92% accuracy are similar. However, by increasing the batch_size and epochs, which give the model more time to train, the accuracy has increased by 3%. To achieve high accuracy, it is sometimes better to test different batch_sizes for a model than to use complicated structures.
