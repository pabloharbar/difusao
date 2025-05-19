# Difusão de calor e massa

This repository solves differential equations for heat and mass diffusion symbolically using Python.

It mainly uses sympy to solve equations and matplotlib + numpy to plot particular results.

Examples were taken from Lista 1 a 7, from diffusion classes.

To run the notebooks with the examples you must have a python environment with **jupyter notebook, numpy, sympy and matplotlib**.

There is a "recipe" to install the environment using the file *pyproject.toml*.

First, install **uv** dependency manager:

```bash
pip install uv
```

Then use uv to install the dependencies:

```bash
uv pip install .
```

This will build a virtual environment under *.venv* folder with the python executable.
Select the corresponding executable to use as a Jupyter Python kernel, specifically for [VSCode](https://code.visualstudio.com/docs/datascience/jupyter-kernel-management)
