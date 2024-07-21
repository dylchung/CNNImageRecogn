[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/xj1INpCM)
# Final Project

This is a **group assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

The final project is due Wednesday, April 24 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/497439/assignments/6023161) in the Canvas assignment.

## Training Data

The training data set is the same for every team in this course.

You can download the training data from the Canvas page:

* ["data_train.npy"](https://ufl.instructure.com/files/85664155/download?download_frd=1)
* ["labels_train.npy"](https://ufl.instructure.com/files/85664157/download?download_frd=1)

## Instructions for Running Our Code

Our model should only be applied to the easy test set.

To train our model, use the train.ipynb file. This file contains the Train() function which takes as inputs vectors X and Y, which are strings which refer to the name of the training data file and the labels file, respectively. Calling this function will train the model and produce the 'CNN.pth' file which will be saved in the current directory.

To test our model on the test data set, use the test.ipynb file. This file contains the Test() function, which takes the parameter X which should be a string representing the file name of the test data set. The Test() function outputs a vector of the predicted labels for each of the test images. In the first cell there are two variables which take the strings representing the test data set and its labels, both should be .npy files. The file predicts the labels for the test data and prints an accuracy score based on the predictions and the true labels.

The following packages are neccessary to run our code

-torch

-torchvision

-PIL

-numpy

Our final model which is loaded by test.py is called Best_Model.pth