# Requierement :

- conda

# Data :

Data use on this project is on <a href = https://static.openfoodfacts.org/data/fr.openfoodfacts.org.products.csv>download here</a>.<br>

unzip file and put on "/Solution/data/"

# Conda environment :

## How to use :

Create environment : <br>
`conda env create --file environment.yaml` <br>

Activate environment : <br>
`conda activate projet3`<br>

Exit current environment : <br>
`conda deactivate projet3`

To remove environment : <br>
`conda env remove --name projet3` <br>

To create environement file (export current environement to file)  : <br>
`conda env export > environment.yaml` <br>

To create environement for the first time : <br>
`conda create --name projet3` <br>

To change channel installer : <br>
`conda config --add channels conda-forge` <br>

To install dependancy : <br>
`conda install <your-dependency> -c conda-forge` <br>

## Add environment to Jyputer notebook :

This tells jupyter to take the current environment("projet3")<br>
`python -m ipykernel install --user --name=projet3`<br>


# Run serve Voila (don't forget to create environment):

Linux / MacOS => Run web application :<br>
`voila P03_02_web.ipynb` <br>
OR<br>
`voila P03_01_notebook.ipynb`<br>

Windows user :<br>
Use cmd script "run_serve_notebook.cmd" to run global notebook or "run_serve_web.cmd" to run prototype.

# Create clean_data.csv

This file can be created with P03_01_notebook, to do this, uncomment cell in "Imputation" that mentions it.
