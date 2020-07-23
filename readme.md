
# CWTS Scientometrics Summer School

This GitHub repository contains the exercises for doing network analysis with Python.

We would like to encourage you to install [Anaconda](https://www.anaconda.com/distribution/) Python locally. This allows you to run the Python notebook on your own computer. As an alternative, the notebook are also available from an online service, if you don't manage to install [Anaconda](https://www.anaconda.com/distribution/) Python locally.

# Local installation

We request you to install Python on your own computer. When you have everything installed locally, you can simply run the notebook, without depending on ony online service. Moreover, you then also have your local environment already setup if you want to use it in the future.

Please follow the following steps to correctly setup your environment:

1. [Download](https://www.anaconda.com/distribution/) and install Anaconda Python. When asked, select to  install it only for a single user.

2. [Download](https://github.com/CWTSLeiden/CSSS/archive/master.zip) this repository and unzip it to a certain directory.

  - For more technical users, you may also clone the repository, make sure that you use the master branch.


3. In Windows, please launch the "Anaconda prompt". In Mac OS/Linux, open the terminal and activate conda by running `source ~/anaconda3/bin/activate`. This enables the installation of the required packages. In the prompt/terminal navigate to the directory to which you unzipped the repository using

    ```
    cd [DIRECTORY]
    ```

    where you should replace `[DIRECTORY]` by the directory where you unzipped the repository.

4. Setup the new environment ``CSSS`` using

    ```
    conda env create -f local/environment.yml
    ```

    This automatically creates the new environment ``CSSS`` and installs the correct versions of all required packages.

    **Note:** Installation may take some time.

## Run Jupyter notebook

There are two ways in which you can run a Jupyter notebook.

1. Launch the "Anaconda navigator" and launch the Jupyter notebook from there. Make sure to select the correct environment ``CSSS`` from the dropdown box at the top of the window. The Jupyter notebook will start in some specific directory, you may need to move the directory to which you unzipped the repository, to ensure it is also visible from Jupyter notebook.

2. In Windows, please launch the "Anaconda prompt". In Mac OS/Linux, open the terminal and activate conda by running ``conda activate CSSS`` or that does not work ``source ~/anaconda3/bin/activate CSSS``. Navigate to the directory to which you unzipped the repository using
    ```
    cd [DIRECTORY]
    ```
    Then launch the Jupyter notebook by
    ```
    jupyter notebook
    ```

In both approaches, you can open the desired notebook: `01-basics.ipynb` or `02-advanced.ipynb`.

## Issues

If encounter any problem during installation, or with the Python notebook, please report it as an issue at https://github.com/CWTSLeiden/CSSS/issues.

# Run online

The Python notebooks can be run online without the need for installation. Please click on one of the badges below to start the interactive environment. Note that the number of resources are limited, and that you cannot use your own data files for further analysis. The online service may also not always be available unfortunately.

## `01-basics.ipynb`
* GESIS (Leibniz Institute for the Social Sciences)
[![Binder](https://notebooks.gesis.org/binder/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/CWTSLeiden/CSSS/master?filepath=01-basics.ipynb)

* PANGEO
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/CWTSLeiden/CSSS/master?filepath=01-basics.ipynb)

* MyBinder.org
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CWTSLeiden/CSSS/master?filepath=01-basics.ipynb)

## `02-advanced.ipynb`

* GESIS (Leibniz Institute for the Social Sciences)
[![Binder](https://notebooks.gesis.org/binder/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/CWTSLeiden/CSSS/master?filepath=02-advanced.ipynb)

* PANGEO
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/CWTSLeiden/CSSS/master?filepath=02-advanced.ipynb)

* MyBinder.org
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CWTSLeiden/CSSS/master?filepath=02-advanced.ipynb)


## `03-prepare-VOSviewer-term-map.ipynb`

* GESIS (Leibniz Institute for the Social Sciences)
[![Binder](https://notebooks.gesis.org/binder/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/CWTSLeiden/CSSS/master?filepath=03-prepare-VOSviewer-term-map.ipynb)

* PANGEO
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/CWTSLeiden/CSSS/master?filepath=03-prepare-VOSviewer-term-map.ipynb)

* MyBinder.org
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CWTSLeiden/CSSS/master?filepath=03-prepare-VOSviewer-term-map.ipynb)
