# Requierement :

- conda

# Data :

Data use on this project is on <a href="https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Impl%C3%A9menter+un+mod%C3%A8le+de+scoring/Projet+Mise+en+prod+-+home-credit-default-risk.zip">download here</a>.<br>

unzip file and put on "/Solution/data/"

# File :

- P04_01_Notebook is a main file contains, P04_01_Model is iteratif testing model.

# Conda environment :

## How to use :

Create environment : <br>
`conda env create --file environment.yaml` <br>

Activate environment : <br>
`conda activate projet4`<br>

Exit current environment : <br>
`conda deactivate projet4`

To remove environment : <br>
`conda env remove --name projet4` <br>

To create environement file (export current environement to file)  : <br>
`conda env export > environment.yaml` <br>

To create environement for the first time : <br>
`conda create --name projet4` <br>

To change channel installer : <br>
`conda config --add channels conda-forge` <br>

To install dependancy : <br>
`conda install <your-dependency> -c conda-forge` <br>

Install requirement file :<br>
`pip install -r requirement.txt`


## Add environment to Jyputer notebook :

This tells jupyter to take the current environment("projet4")<br>
`python -m ipykernel install --user --name=projet4`

