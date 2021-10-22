# os6025_project
_repository for simulation scripts used for our operating systems project_


See `notebooks\Analysis.html` to see a copy of the notebook


> I'm not sure how much we'll use this, I'm just kinda playing around right now

## Getting Started

### Creating the Environment
* Option 1 (pip)
    - Install python from https://www.python.org/downloads/ if you don't already have it.
    - From within a terminal, navigate to the root folder that this document is in.

    ```bash
        C:\users\USERNAME>cd PATH/TO/os6025_project
    ```
    - Install the required libraries
    ```bash
        python -m pip install -r requirements.txt
    ```


* Option 2 (conda)
    - (If you don't have it already) Install `Miniconda` from https://docs.conda.io/en/latest/miniconda.html _(Anaconda is also fine)_
    - Open up a conda terminal.<br>
       - From the start menu, search for `Anaconda` and `Anaconda Prompt (Miniconda3)` should pop up.<br>
       - The terminal should look like this

    ```bash
        (base) C:\users\USERNAME>
    ```
    - From within the terminal, navigate to the root folder that this document is in.

    ```bash
        cd PATH/TO/os6025_project
    ```
    - Create the project environment.<br>
      This will create a python environment with all of the libraries required to run the notebooks

    ```bash
        conda env create -f environment.yml --prefix ./envs/os-project
    ```

    - Activate the new environment

    ```bash
        conda activate envs/os-project
    ```
    > `(base) ...` Should now be `(os-project) ...`
 

## Running the Notebook
- With the environment active launch `jupyterlab` via
```bash
(os-project) ...\os6025_project>jupyter lab
```

> This will open up a new tab in a web-browser

- Open the `notebooks/` folder and double click `Analysis.ipynb` to open the notebook.
- To run a single cell, click on it and press `Shift` + `Enter`
- To run all cells click on `Kernel` (in the toolbar) and then `Restart Kernel and Run All`


