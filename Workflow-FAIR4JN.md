## FAIR for Jupyter Notebook Workflow

This workflow outlines a step by step approach in creating a FAIR Jupyter Notebook. (30 minutes)

1. Sign in to github, click on + sign beside your login to create a new github repository. Fill in the form to create a new repository with license information. Alternatively, you can add licensing information at a later stage by adding a license file named "LICENSE". Make sure to edit the license file with contributors names and year.  

    [A guide to creating a license](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)
    
    ![alt text](https://github.com/Aleem2/FAIR4JupyterNotebook/blob/Images-in-workflow/images/license-tool.webp?raw=true)
         
2. Metadata is a way to provide author details and the ability to cite the software. We recommend using CITATION.cff file, which provides a machine readable format to reference the said work.


    [A guide to creating CITATION.cff - metadata file](https://citation-file-format.github.io/)
    
    <pre><code>
    cff-version: 1.2.0
    message: "If you use this software, please cite it as below."
    authors:
      - family-names: Uddin
        given-names: Aleem
        orcid: https://orcid.org/0000-0002-8519-5534
    title: "My Research Software"
    version: 2.0.4
    doi: 10.5281/zenodo.7690164
    date-released: 2021-08-11  
    </code></pre>

3. Upload the Jupyter Notebook file, so that it becomes findable and accessible via the github repository.


4. Reproducibility of the Jupyter Notebook is ensured by providing the dependencies using requirements.yml file.    


    [A guide to creating requirements.yml](https://mybinder.readthedocs.io/en/latest/howto/languages.html)


    * Tips on finding the dependencies from a working Jupyter notebook on your desktop.
   
   
        * In a new cell, use the following command to get all libraries
        ~~~~
        ! freeze | grep -i numpy # Say getting a numpy version only. And do the same for other libraries
        ~~~~
         
        * Inside the jupyter notebook use the following command to get the python version.
        ~~~~
        ! python -version
        ~~~~

5. Additionally, we recommend creating a bindhub and google Colab, or ‘Colaboratory’ badges. The badges can be clicked upon to launch Jupyter Notebook in a reproducible manner.
   
    [A guide to creating an executable binderhub badge](https://mybinder.readthedocs.io/en/latest/introduction.html)

6. Create Google colab badge which can be executed. (caveat dependencies ignored)
   
    [A guide to creating google colab badge](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb#scrollTo=-pVhOfzLx9us)

7. Persistent Identifier (DOI) - Assign a persistent identifier (DOI) to the repository, once the research is completed. GitHub has a thorough guide on generating DOI’s with a Zenodo plugin.

    7.1 Login to Zendo and click on the "link to github".
         
    [A guide to creating DOIs](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)

8. Publish the repository to get DOI and the DOI badge, which can be updated in readme.md

9. Finally update the citation.cff files with DOI link.
