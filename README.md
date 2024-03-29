# A cautionary tale about deep learning based climate emulators
Code for ICLR24 CCML Paper submission.

This code explains the linear pattern scaling model via a Jupyter notebook tutorial. The tutorial is also intended to help readers get started with machine learning for climate modeling. To read the tutorial go to:

[climate_emulator_tutorial.ipynb](https://nbviewer.org/github/ygaxolotl/tags-linear-pattern-scaling/blob/main/climate_emulator_tutorial.ipynb)

The results of linear pattern scaling on ClimateBenchv1.0 can be reproduced with a 2nd notebook (see below).

# Installation
```
git clone git@github.com:ygaxolotl/tags-linear-pattern-scaling.git
cd tags-linear-pattern-scaling
conda create --name emcli
conda activate emcli
conda install pip
pip install -r requirements.txt
pip install -e .
ipython kernel install --user --name=emcli # Link conda environment to jupyter notebook
```

# Start the notebook tutorial
```
jupyter notebook climate_emulator_tutorial.ipynb
```

# Reproduce linear pattern scaling table on ClimateBenchv1.0 for all climate variabes
```
jupyter notebook notebooks/calculate_climatebench_metrics.ipynb
```
