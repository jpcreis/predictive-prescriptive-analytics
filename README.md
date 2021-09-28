# Predictive & Prescriptive Analytics for Laser Seam Welding

This repository presents the implementation of a predictive model for product quality based on machine parameters in a laser seam welding process. Additionally, a prescriptive model was developed using meta-heuristic algorithms to find the best machine parameter once a new product quality is required.

For all the code snippets and plots please open the Jupyter Notebook named "predictive_prescriptive_analytics.ipynb". The folder dataset contains all the relevant CSVs, including the original dataset and post-processed ones. For the presented scenario, the dataset label as "no_keyhole" was used.

## Create an Anaconda environment
`conda create --name machine_intelligence`

## Activate the environment (if not activated)
`conda activate machine_intelligence`

## Install ipykernel to allow the new environment as a Kernel
`conda install -c anaconda ipykernel`

## Associate the environment to the Jupyter Notebook
`python -m ipykernel install --user --name=firstEnv`

## Installing all dependencies
`pip install –r requirements.txt`

## List all environments
`conda env list`

## deactivate current environment
`conda deactivate`

## Remove an environment
`conda remove –name myenv --all`

## List all packages in an environment
`conda list -n myenv`
