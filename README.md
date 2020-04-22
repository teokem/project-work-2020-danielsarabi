## Getting started with the jupyter notebook

Please use the following steps in order to get started:

1. Install minconda or anaconda (this can be used to install jupyter notebook and other python software)

2. Download the repository from GitHub

3. In your terminal, cd into the dowloaded directory

4. Create environment by using the daniel_project.yml file

    - look for a file named daniel_project.yml containing the necessary software packages required to run the notebook
    - create the new eviroment using the follwing commands in your terminal

    ```.py
    conda env create -f daniel_project.yml
    ```
5. Activate the environment

    ```.py
    conda activate jupyter_project
    ```
6. Check the contents of the environment by typing

    ```.py
    conda list
    ```

7. Check also what environments you have. You should see jupyter_project in this list

    ```.py
    conda env list
    ```
8. Install ipykernel - Allows you to use the environment as a kernel in Jupyter

```.py
pip install --user ipykernel
```


9. Using ipykernel, to get the environment to Jupyter

```.py
python -m ipykernel install --user --name=myenv
```

10. Run jupyter notebook from the command-line in terminal

    ```.py
    jupyter notebook
    ```
