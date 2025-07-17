# Spring_AA_InternalVariability

This repository holds code relevant to Gale et al., 2025 (in prep).

Arctic_CNN: This notebook contrains the training, testing, and validation for the hyperparameter-optimized Arctic CNN. Data load paths will need to be altered depending on where user downloads simulation training and observational data.

Global_CNN: This notebook contrains the training, testing, and validation for the hyperparameter-optimized Global CNN. Data load paths will need to be altered depending on where user downloads simulation training and observational data.

environment.yml: This .yml file contains all of the libraries needed to execute the CNN code. This can be used to set up a new kernel for the user to make running the CNNs easier.

Dynamic_Adjustment: This notebook contains the code for the partial least squares dynamic adjustment method based on Wallace et al., 2012 and Smoliak et al., 2015.

The processed data that is used in these notebooks is located in [Zenodo](https://zenodo.org/records/16059348?preview=1&token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjU5YzQzMjY5LTJiNTItNDA1ZC04MjgxLTdlZWQyM2U5OTZiMCIsImRhdGEiOnt9LCJyYW5kb20iOiIxOGI4OWE0ZmQxNTk5ZWFhMDI0YzY3NjM0M2RiYmM5ZiJ9.F_UHerumf6Q0NaZ0FNtGmdDy-GjtcwonsQtuayYMjn4Ml5mJA_baaVMsOdOVRiVPusAHXgf3p6N9XiauaQaykw). 

Note: All CNN training for the manuscript was done using 1 Tesla GPU on NCAR's Computational and Information Systems Laboratory Casper server.
