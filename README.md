# EuroPython 2019: Functional Programming with Python
I hosted an interactive session about functional programming 
at the EuroPython 2019 in Basel, using this Jupyter notebook.

Due to high degrees of interest in functional programming and parallelism, as well as the [coconut](http://coconut-lang.org/) language, I added a lightning talk briefly covering these two topics.

## Install
Simply run on Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eliasmistler/europython2019-python-fp/master)

If you prefer to run this on your own machine, create a Python 3 virtualenv, install the requirements and start jupyter:

```bash
virtualenv -p python3 .venv
. .venv/bin/activate
pip install -r requirements.txt
jupyter lab  # or `jupyter notebook` if you prefer
```

*Note*: I pinned all requirements as they worked for me. Feel free to update them, everything *should* work the same in newer versions.

## Re-use
Feel free to re-use, change and publish the notebooks in any setting (MIT Licence) - please just link back to this GitHub repo as your source.

The notebook is set up to work as an interactive presentation using [RISE](https://rise.readthedocs.io), a simpe-to-use jupyter plugin.
