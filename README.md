# Jupyter-Notebook-Stack

## Installing Jupyter Notebook 
- tool for data scientists
- IDE vs interactive environment 
### Data science workflow
- set up an experiment
- supply initial parametes or input
- run the experiment
- gather results
- tweak parameters
### Jupyter Notebook timeline
- f12 chrome developer tools
- JS console to execute the small texts in FE dev
#### REPL read evaluate print loop
- IPython 
# IPython notebook 
- starts a local web server
- runs python session in browser called notebooks
- persisted to disk 
- share with others 
- push an IPython notebook file to github and it will render a static version 
- creates visualizations inline
- comment using markdown

# Jupyter notebook (IPython + new features)
- plugin languages like R F# 
- shell was renamed to jupyter
- free opensource and cross platform

## Installation
- Python pip packet manager
- install using Anaconda 
- large install fr everything 
- Docker for preinstalled notebooks
- Azure notebooks 

## After installation 
- open cmd
- >jupyter notebook
- opens jupyter on licalhost 8888
- with default web browser at localhost8888/tree
- ctrl c twice to stop the notebook
- >jupyter notebook --port=8889 --ip=127.0.0.1 
- >jupyter notebook --notebook_dir=notebook_path 

## docker
- download docker installer and run it
- >docker pull jupyter/datascience
- downloads the image fr DS
- >docker run --it --rm jupyter/datascience-notebook
- need to connect the host os to the docker server thats running 
- >docker run --it --rm -p 8888:8888 jupyter/datascience-notebook
- map a volume in the container to the host os
- >docker run --it --rm -p 8888:8888 -v C:\ady\notebooks:/home/dockady jupyter/datascience-notebook
- change permissions for docker settings in the toolsbar on desktop 
- shared drives and choose C:

# Azure notebooks
- Navigate to notebooks.azure.com and signin
- In azure notebooks are stored in libraries
- create a new library with a unique id
- in the new lib create a new notebook
- choose file type as python 3.x
- timeout if you dont use them fr a while
