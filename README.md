# Physics of disordered systems: Jupyter notebooks

These Jupyter notebooks are also [accessible on binder](https://mybinder.org/v2/git/https%3A%2F%2Fframagit.org%2Fcoslo%2Fdisordered.git/HEAD)

## Themes

### Introduction

- [fit.ipynb](https://framagit.org/coslo/disordered/-/blob/master/fit.ipynb)

### Colloids

- [rw.ipynb](https://framagit.org/coslo/disordered/-/blob/master/rw.ipynb)
- [brownian.ipynb](https://framagit.org/coslo/disordered/-/blob/master/brownian.ipynb)
- [active.ipynb](https://framagit.org/coslo/disordered/-/blob/master/active.ipynb)

### Polymers

- [dna.ipynb](https://framagit.org/coslo/disordered/-/blob/master/dna.ipynb)
- [saw.ipynb](https://framagit.org/coslo/disordered/-/blob/master/saw.ipynb)

### Effective interactions

- [interactions.ipynb](https://framagit.org/coslo/disordered/-/blob/master/interactions.ipynb)

### Liquids

- [statics.ipynb](https://framagit.org/coslo/disordered/-/blob/master/statics.ipynb)
- [dynamics.ipynb](https://framagit.org/coslo/disordered/-/blob/master/dynamics.ipynb)

### Supercooled liquids

- [supercooled.ipynb](https://framagit.org/coslo/disordered/-/blob/master/supercooled.ipynb)

## Installation

To execute the notebooks on your computer (linux or mac), make sure `git` is installed and follow the instructions below.

From a terminal, clone this repository
```
git clone https://framagit.org/coslo/disordered.git
cd disordered
```

Install required python packages in a python virtual environment
```
python3 -m venv env
. env/bin/activate
pip install -r requirements.txt
```
Note: if the `venv` module is not available in your python distribution you can either install it ot use `virtualenv` instead.

Get started with jupyter notebooks
```
jupyter notebook
```

The command `deactivate` (from the terminal) brings you back to the default python environment.

