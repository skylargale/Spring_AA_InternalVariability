# spring-aa-internalvariability

Code accompanying [Gale et al. (2026)](https://doi.org/10.1175/JCLI-D-25-0421.1).

## Repository Contents

### Notebooks

- `Arctic_CNN.ipynb`  
  Training, testing, and validation of the hyperparameter-optimized Arctic CNN.

- `Global_CNN.ipynb`  
  Training, testing, and validation of the hyperparameter-optimized Global CNN.

- `Dynamic_Adjustment.ipynb`  
  Partial least squares dynamic adjustment method following Wallace et al. (2012) and Smoliak et al. (2015).

- `Make_Figures.ipynb`  
  Code used to generate all manuscript figures and supplementary material.

## Setup

The `environment.yml` file contains the required Python libraries and dependencies.

Create the Conda environment:

```bash
conda env create -f environment.yml
```

Activate the environment:

```bash
conda activate spring-aa-internalvariability
```

Register the environment as a Jupyter kernel:

```bash
python -m ipykernel install --user \
    --name spring-aa-internalvariability \
    --display-name "spring-aa-internalvariability"
```

## Data Availability

Processed data used in this repository is available on Zenodo:

- Code archive: [https://zenodo.org/records/20040203](https://zenodo.org/records/20040203)
- Data archive: [https://zenodo.org/records/16059348](https://zenodo.org/records/16059348)

## Notes

CNN training for the manuscript was performed on an NVIDIA Tesla GPU using the Casper system at the NSF NCAR Computational and Information Systems Laboratory (CISL).

File paths within notebooks may need to be modified depending on local data storage locations.

## Citation

If you use this code, please cite:

```text
Gale, S. (2026). spring-aa-internalvariability (Version 1.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.20040202
```
