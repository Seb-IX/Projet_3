# Requierement :

- pip
- conda

# Data :

Data use on this project is on <a href = https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/AI+Engineer/Project+2+Participez+%C3%A0+un+concours+sur+la+Smart+City/p2-arbres-fr.csv>on download here</a>.


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
`python -m ipykernel install --user --name=projet3`

