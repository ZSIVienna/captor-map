# Captor Map

Visualization of static ozone measurement stations in Italy, Spain and Austria

## URL
https://map.captor-project.eu/2017
https://map.captor-project.eu/2018

## Information
The static html files are generated with the IPython notebook. It generates an index.html file and for each location an html file which is included in the map as an iframe. The jupyter-notebook (https://jupyter.org/) will process data from two different formats, the "captor"-format and "raptor"-format.

### How to run the notebook
1. Create pip or pipenv environment
2. Clone the repository
3. Install requirements
4. Start the notebook
5. Have fun

Start the notebook
    
    jupyter notebook


If you do not want to start a jupyter notbook in the browser you can also execute all cells from the command line with this command:
    
    jupyter nbconvert --to notebook --execute CAPTOR_MAP.ipynb

Further documentation regarding jupyter-notebooks can be found here:

https://jupyter-notebook.readthedocs.io/en/stable/
