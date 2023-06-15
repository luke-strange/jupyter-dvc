# jupyter-dvc
An experiment to use jupyter notebooks with DVC 

# WSL
It's helpful to have windows subsystem for linux, or any kind of virtual linux machine installed on your computer. Enter this environment with `bash` or other similar commands from a terminal.

# Pipenv
You must have [pipenv](https://pypi.org/project/pipenv/) installed. Clone the repository and run `pipenv shell` in the `jupyter-dvc` directory to activate the virtual environment. Run `pipenv install` to install the dependencies.

# DVC
Run the pipeline using `dvc repro notebooks/dvc.yaml`. Change parameters in `notebooks/params.yaml` to alter the notebook's output.

# Mercury
You can launch the interactive notebook from within the `mercury` folder in the terminal using `mercury run`.
