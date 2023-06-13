# jupyter-dvc
An experiment to use jupyter notebooks with DVC 

# Pipenv
You must have [pipenv](https://pypi.org/project/pipenv/) installed. Clone the repository and run `pipenv shell` to activate the virtual environment. Run `pipenv install` to install the dependencies.

# DVC
Run the pipeline using `dvc repro notebooks/dvc.yaml`. Change parameters in `notebooks/params.yaml` to alter the notebook's output.