# Tutorial for Machine Learning with Large Datasets

## Problem 

Data can easily exceed memory, and we cannot load it all at once. Training a machine learning algorithm requires only one batch of data at a time, a tiny fraction of the overall dataset. Therefore, it can be efficient to load data only when needed. This repository collects notebooks for a demo machine learning algorithm using a large dataset. We cover the following frameworks:

- [x] Pytorch Lightning 2.4.0
- [x] Tensorflow
- [x] Keras

## Install

Create a virtual environment

```
module load python3
python3 -m venv --system-site-packages .venv
```

Install the machine learning packages via pip

```
source .venv/bin/activate
pip install -r requirements.txt
```

Create Jupyterhub kernel

```
python -m ipykernel install --user --name tutorial_ml --display-name="Tutorial Machine Learning"
```

Use this kernel ("Tutorial Machine Learning") to run the notebook corresponding to your framework of choice.