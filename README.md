# Content
Folder CAM includes a jupyter notebook,as well as the postprocessed CAM data, to create Fig. 2 in the paper.
Folder column_model includes two notebooks to create Fig. 1a (Radiative_cooling_CO2.ipynb) and Fig. 3 (Radiative_cooling_climate_sweep.ipynb)
The notebook fofB.ipynb generates Fig. 1b. 

# Requirements
Beyond standard Python packages, the column_model scripts require the climlab package (https://climlab.readthedocs.io/en/latest/intro.html).
The scripts were tested using python version 3.7.10 and climlab version 0.7.13, but should be compatible with other recent python and climlab distributions. 

# Instructions
The notebooks can be run (and edited) in the juypter notebook environment on a standard laptop or desktop computer. All notebooks can be run in minutes, except "Radiative_cooling_climate_sweep.ipynb", which may take tens of minutes to compute all climate scenarios.
