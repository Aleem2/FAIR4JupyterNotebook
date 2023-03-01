# FAIR4JupyterNotebook

## A FAIR Jupyter Notebook - (Metadata: ARDC template: Jupyter Notebook, Findable, Accessible, Interoperable, Reproducible) 

### This is an example FAIR jupyter notebook repo and it serves as a guide to researchers.

### The example file is sourced from matplotlib example files. 

https://matplotlib.org/stable/gallery/statistics/boxplot_vs_violin.html#sphx-glr-gallery-statistics-boxplot-vs-violin-py

## Code dependencies 

The code dependencies are captured in the environments.yaml file following the instructions from the link below.

https://mybinder.readthedocs.io/en/latest/howto/languages.html

To get the list of python packages and dependencies use below command from jupyter notebook. This inststruction is not part of the .ipnby file. 
! freeze

! freeze | grep -i numpy # getting numpy version only.

! freeze | grep -i matplotlib # getting matplotlib version only. 


