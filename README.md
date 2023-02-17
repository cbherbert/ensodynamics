# ENSO dynamics

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cbherbert/ensodynamics/HEAD)

This repository contains a Jupyter notebook used for a class about climate variability in the Masters program at the Department of Physics at *ENS de Lyon*.

The goal is to study a very simple conceptual model of the dynamics of the *El Niño Southern Oscillation*, the Jin model.

## How to use

### Using with an existing python installation

The notebook requires only standard packages: `numpy`, `matplotlib` and `scipy`.
If you have an existing installation with these modules (and `jupyter`), simply download the notebook, run a jupyter server and open the notebook on your local machine.

### Virtual environment

If you prefer to use a virtual environment with the exact versions of the packages which were used to write the notebook, open a terminal and type the following commands:

```
git clone https://github.com/cbherbert/ensodynamics
cd ensodynamics
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip install jupyter
jupyter notebook enso-dynamics.ipynb
```

### Cloud computing

You can use this notebook without installing or downloading anything on your machine, by using Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cbherbert/ensodynamics/HEAD)
