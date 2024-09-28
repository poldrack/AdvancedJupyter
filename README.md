### Advanced Jupyter topics

- The structure of a .ipynb file
- Why ipynb files don't play nicely with version control
- Using jupytext 
- Using VSCode with jupyter notebooks: https://code.visualstudio.com/docs/languages/python#_jupyter-notebooks
- Code linting and formatting
- Magic commands: https://ipython.readthedocs.io/en/stable/interactive/magics.html
- Executing jupyter notebooks from the command line using nbconvert

### Setting up the environment

If you want to set up your environment to run the code, you can do the following:

1. Install the [uv package management system](https://github.com/astral-sh/uv)
2. Clone this git repository and cd into the directory
3. run `uv pip install -r pyproject.toml` to install the python packages
4. run  `uv venv` to set up the virtual environment
5. run `source .venv/bin/activate` to activate the virtual environment.


#### Resources

- https://www.dataquest.io/blog/advanced-jupyter-notebooks-tutorial/
