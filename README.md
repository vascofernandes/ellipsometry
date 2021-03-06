# Ellipsometry
The aim of this project is numerical analysis of a [data set from ellipsometric measurements](https://en.wikipedia.org/wiki/Ellipsometry)
 (psi and delta) in Python. It finds optimal fit of a set of parameters of an optical model of the sample using bounded non-linear fitting. Currently it is suitable for analysing measurements taken at one wavelength and multiple angles of incidence. It can be easily modified to perform analysis on data gathered at multiple wavelengths (so called VASE ellipsometry).

The scripts in this project use scientific computing libraries from open science platform Anaconda.
It can be downloaded here: https://www.continuum.io/downloads.

**Package *lmfit* is used for bounded non-linear fitting.**
More info about the package is available at https://lmfit.github.io/lmfit-py/intro.html.
It can be installed using command line: conda *install -c conda-forge lmfit*.
More info about *lmfit* package installation can be found at https://lmfit.github.io/lmfit-py/installation.html.

User should first try to run *Test fit from "lmfit" documentation - decaying sine wave.py* to see if everything is working correctly.

For data analysis use either plain Python notebook *Two layer model.py* or Jupyter notebook *Two layer model.ipynb*. The Jupyter notebook already contains some sample plots.
