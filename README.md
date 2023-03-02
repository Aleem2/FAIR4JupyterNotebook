# FAIR4JupyterNotebook

## A FAIR Jupyter Notebook - (Metadata: ARDC template: Jupyter Notebook, Findable, Accessible, Interoperable, Reproducible) 

### This is an example FAIR jupyter notebook repo and it serves as a guide to researchers.

The example file is sourced from matplotlib example files. 

https://matplotlib.org/stable/gallery/statistics/boxplot_vs_violin.html#sphx-glr-gallery-statistics-boxplot-vs-violin-py

A binderhub badge to instantly launch the notebook. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Aleem2/FAIR4JupyterNotebook/HEAD?labpath=boxplot_vs_violin.ipynb)

## Code dependencies 

The code dependencies are captured in the environment.yaml file. The instructions about create one for your project can be found at the link below.

https://mybinder.readthedocs.io/en/latest/howto/languages.html

To get the list of python packages and dependencies use the following commands in jupyter notebook. This inststruction commands are not part of the notebook .pynb file. 

! freeze

! freeze | grep -i numpy # getting numpy version only.

! freeze | grep -i matplotlib # getting matplotlib version only. 
