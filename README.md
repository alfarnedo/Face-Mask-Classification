### Face Mask Classification

## Overview

**Description**

This is the solution given to a Kaggle challenge proposed by a teacher of a master’s degree course.

An "AI" artificial intelligence solution must be developed to identify whether a person is wearing a face mask or not.

For this, the construction of a simple facial mask detection system is offered as a solution in this challenge, using the deep learning technique called "Convolutional Neural Networks". This model could also be used to develop a complete software that scans all people prior to their entry into any public space and thereby minimize risks of contagion.

The objectives of this challenge were:

    * Create a convolutional neural network “CNN” to classify facial images to identify whether or not the person in the image had a facial mask. 
    * Calculate the probability that each test image is a person wearing a face mask.
    * Calculate the AUC value, representing the ROC curve. 
    * Represent the confusion matrix. 
    * Generate a. csv file with your estimates to send the solution to the Kaggle platform.

For this purpose, labelled training data and unlabelled test data were provided. 

There are about 2k training pictures of people wearing facial masks and about 7k training pictures of people not wearing facial masks.

To carry out this project, different GitHub repositories, open source and forums were used, whose links are the following:
  * [*CREATE A CNN NETWORK (GITHUB REPOSITORY)*](https://github.com/mk-gurucharan/Face-Mask-Detection/) 
  * [*CREATE A CNN NETWORK (PYTORCH FORUM)*](https://pytorch.org/docs/stable/generated/torch.nn.Conv2d.html)
  * [*EARLY STOPPING FUNCTION (GITHUB REPOSITORY)*](https://github.com/Bjarten/early-stopping-pytorch)
  * [*ADAM OPTIMIZER*](https://medium.com/@Biboswan98/optim-adam-vs-optim-sgd-lets-dive-in-8dbf1890fbdc)


## FILES
This project has the following folder distribution: 
  * Readme.md, the file you are currently reading.
  * src/Face Mask Classification: 
      * code --> In this folder is the file . ipynb with the code.
      * data:
        * test --> In this folder are the test images.
        * train --> In this folder are the training images.
        * testLabels.csv --> In this folder is the ". csv" file which contains the test tags, to evaluate the efficiency of the classifier.
