### FAIR for Jupyter Notebook Workflow 

* Create a github repo with license. Or add a lincense file "LICENSE" and insert license.

* Create CITATION.cff and update details

* Upload Jupyter notebook file

* Follow https://mybinder.readthedocs.io/en/latest/howto/languages.html to create requirements.yml file

         * Inside jupyternote book use command ! freeze | grep -i numpy # getting numpy version only. And do the same for other libraries
         
         * Inside jupyternote book use command ! python -version 

* Create binder badge following link, https://mybinder.readthedocs.io/en/latest/introduction.html

* Create Google colab badge following instructions https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb#scrollTo=-pVhOfzLx9us

* Login to Zendo and click on the link to github. 

         * Toggle the switch to the link repository. 

* Publish the repository to get DOI and the DOI badge, which can be updated in readme.md and citation.cff files.
