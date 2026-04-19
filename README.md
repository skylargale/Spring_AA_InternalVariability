# spring-aa-internalvariability

This repository holds code relevant to [Gale et al., 2026](https://doi.org/10.1175/JCLI-D-25-0421.1).

## Setup Instructions

The `environment.yml` file contains all of the libraries needed to execute the CNN code. This can be used to set up a new kernel with all the libraries and dependencies. From the project root directory, run:

```conda env create -f environment.yml```

Activate the environment:

```conda activate my-kernel```

Register the environment as a Jupyter kernel:

```python -m ipykernel install --user --name my-kernel --display-name "my-kernel"```

## Notebooks

`Arctic_CNN.ipynb`: This notebook contains the training, testing, and validation for the hyperparameter-optimized Arctic CNN. Data load paths will need to be altered depending on where user downloads simulation training and observational data.

`Dynamic_Adjustment.ipynb`: This notebook contains the code for the partial least squares dynamic adjustment method based on Wallace et al., 2012 and Smoliak et al., 2015.

`Global_CNN.ipynb`: This notebook contains the training, testing, and validation for the hyperparameter-optimized Global CNN. Data load paths will need to be altered depending on where user downloads simulation training and observational data.

`Make_Figures.ipynb`: This notebook contains all code needed to make the figures and supplemental shown in Gale et al., 2026 (in revision).

Note: All CNN training for the manuscript was done using 1 Tesla GPU on NCAR's Computational and Information Systems Laboratory Casper server.

## Data

The processed data that is used in these notebooks is located in [Zenodo](https://zenodo.org/records/16059348?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjU5YzQzMjY5LTJiNTItNDA1ZC04MjgxLTdlZWQyM2U5OTZiMCIsImRhdGEiOnt9LCJyYW5kb20iOiIxOGI4OWE0ZmQxNTk5ZWFhMDI0YzY3NjM0M2RiYmM5ZiJ9.F_UHerumf6Q0NaZ0FNtGmdDy-GjtcwonsQtuayYMjn4Ml5mJA_baaVMsOdOVRiVPusAHXgf3p6N9XiauaQaykw).
