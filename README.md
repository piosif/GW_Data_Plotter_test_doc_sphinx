# GW Data Plotter
GW Data Plotter is a desktop application that simplifies access to Gravitational Wave (GW) data and facilitates basic 
visualization and analysis. 
This reposity contains the source files to run the GW Data Plotter App from a python script. 
The code is based on [PyQt6](https://www.riverbankcomputing.com/software/pyqt/) for the graphical interface, and
[gwpy](https://gwpy.github.io) and [gwosc](https://pypi.org/project/gwosc/) python packages for the gravitational wave 
related part.

## Description of the python scripts
This repository contains 3 python scripts:
* `gw_data_plotter.py`: main script; to get the app just execute on a terminal `python gw_data_plotter.py`
* `layout.py`: it is imported by the main script and contains the details of the layout of the app
* `app_resources.py`: it is imported by the main script and contains the resources used by the app

## Conda environment
To run the code you will need to set up an appropriate conda environment. 
We provide yml files so that you can build directly the conda environment for your machine in the folder `conda_environments`. 
You can select the environment more suited for your Operating System (OS) and then create the environment with:

`conda env create --file environment.yml`

(replacing environment.yml with the appropriate name of the environment file for your machine). And activate it with:

`conda activate app`

Use:
* `environment_WindowsOS.yml` for Windows Operating Systems 
