# Jungblut_Loew_etal_2026

Imaris 11.0 workflow for interaction site segmentation and Python scripts and jupyter notebooks analysis of Imaris-surface data.
Note: running the Imaris Workflow file requires Imaris version 11.0 or newer with machine learning assisted segmentation.

This code is a supplement to the publication Jungblut-Loew et al. 2026.

The analysis code is presented as Jupyter notebooks that make use of python 3.12 and python-based libraries as outlined in the environment.yml files.

# Installation
The required packages are defined in environment.yml. Create the Conda environment using Mamba (recommended):

mamba env create --file environment.yml

Alternatively, use Conda:

conda env create --file environment.yml

Activate the environment and start JupyterLab:

conda activate pd1-pdl1-analysis jupyter lab

# License
Distributed under the terms of the BSD-3 License, this code is free and open-source software.


