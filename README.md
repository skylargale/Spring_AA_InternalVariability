# Spring_AA_InternalVariability

This repository holds code relevant to Gale et al., 2025 (in prep).

Arctic_CNN: This notebook contrains the training, testing, and validation for the hyperparameter-optimized Arctic CNN. Data load paths will need to be altered depending on where user downloads simulation training and observational data.

Global_CNN: This notebook contrains the training, testing, and validation for the hyperparameter-optimized Global CNN. Data load paths will need to be altered depending on where user downloads simulation training and observational data.

environment.yml: This .yml file contains all of the libraries needed to execute the CNN code. This can be used to set up a new kernel for the user to make running the CNNs easier.

Dynamic_Adjustment: This notebook contains the code for the partial least squares dynamic adjustment method based on Wallace et al., 2012 and Smoliak et al., 2015.

data: This folder holds all of the data needed to train, test, and validate the Arctic and global CNNs as well as perform the dynamic adjustment.

Note: All CNN training for the manuscript was done using 1 Tesla GPU on NCAR's Computational and Information Systems Laboratory Casper server.
