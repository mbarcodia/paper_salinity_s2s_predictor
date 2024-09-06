# salinity_s2s_predictor

## Overview
This is the code for the paper titled "Sea Surface Salinity Provides Subseasonal Predictability for Forecasts of Opportunity of U.S. Summertime Precipitation" submitted to Journal of Geophysical Research: Atmospheres by Arcodia et al. 

## Tensorflow 
This code was written in python 3.9.7 and tensorflow 2.15.0. Below is my environment: 

conda create -n tf2 python=3.9.7
conda activate tf2
conda install -c conda-forge jupyterlab cartopy
conda install xarray scikit-learn seaborn palettable python-graphviz
pip install tensorflow==2.15.0 (original code used tensorflow 2.5, but updates caused conflicts and tensorflow 2.15.0 was compatible without changing code output)
pip install netcdf4 keras_tuner pydot pydotplus ipynb-py-convert import-ipynb latex

## Credits
The co-authors on this work include Marybeth C. Arcodia (CSU), Elizabeth A. Barnes (CSU), Paul J. Durack (LLNL), Patrick W. Keys (CSU), Juliette Rocha (Texas A&M)

CSU: Department of Atmospheric Science, Colorado State University, Fort Collins, CO, USA.
LLNL: Program for Climate Model Diagnosis and Intercomparison (PCMDI), Lawrence Livermore National Laboratory, Livermore, CA, USA.
Texas A&M: Department of Atmospheric Science, Texas A&M University, College Station, TX, USA

## Paper citation
will be included upon acceptance for publication

