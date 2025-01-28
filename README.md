# conda_envs_for_pipelines
This is where I will keep track of all of the conda environments I have made for any pipelines

'''
here is a little note on how i built an ngsplot environment so it can acutally work
# i can probably just comment all of this out since it is saved in the yml file
    # using this version of r 4.2.3
    conda install conda-forge::r-base=4.2.3 -y 
    # try this ( it works all four lines uncomment)
    conda config --add channels bioconda
    conda config --add channels conda-forge
    conda config --set channel_priority strict
    conda install bioconductor-shortread -y

    # now need BSgenome
    conda install bioconductor-bsgenome -y 

    # this ensures i can use the zip feature without any problems
    conda install conda-forge::zip -y
    
    # lets try the next steps with a conda install of domc and catools so it is saved in the exported yml file
    conda install conda-forge::r-domc -y
    conda install conda-forge::r-catools -y
'''
