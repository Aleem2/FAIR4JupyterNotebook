### FAIR for Jupyter Notebook Workflow 

This workflow outlines a step by step approach in creating a FAIR Jupyter Notebook.

* Sign in to github, click on + sign beside your login to create a new github repo. Fill in the form to create a new repository, you can add licensing information or add it at a latter stage by adding a lincense file "LICENSE" and insert license. Make sure to update the license details such as contributers names and year.  

    [A Guide to creating a license](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)
         
* Create CITATION.cff and update details. Detailed process is on the link, https://citation-file-format.github.io/. 

* Upload Jupyter notebook file

* Follow the link (https://mybinder.readthedocs.io/en/latest/howto/languages.html) to create requirements.yml file

         * Inside jupyternote book use command ! freeze | grep -i numpy # getting numpy version only. And do the same for other libraries
         
         * Inside jupyternote book use command ! python -version 

* Create binder badge following link, https://mybinder.readthedocs.io/en/latest/introduction.html

* Create Google colab badge following instructions https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb#scrollTo=-pVhOfzLx9us

* Login to Zendo and click on the link to github. 

         * Toggle the switch to the link repository. 
         
         * How to create DOI is detailed in the web resource. https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content.

* Publish the repository to get DOI and the DOI badge, which can be updated in readme.md and citation.cff files.
[ARCOS](arcos.ardc.edu.au)
