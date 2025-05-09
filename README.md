# Heart Failure Prediction

**Author:** Charles Milton 
**Date:** 05/08/2025

## Overview

This repository contains a Jupyter Notebook (`HeartFailurePrediction.ipynb`) that predicts heart disease using patient vitals and ECG readings.  
It covers data preprocessing, model training, hyperparameter tuning, feature selection, ensembling, and evaluation.

## Files

- `HeartFailurePrediction.ipynb`: Main Jupyter notebook.  
- `heart.csv`: Dataset file (place in same directory).  
- `environment.yml`: Conda environment specification.  
- `requirements.txt`: Pip requirements file.

## Setup

### Conda Environment

```bash
conda env create -f environment.yml
conda activate heart-failure-env
```

### Pip Install

```bash
pip install -r requirements.txt
```

## Running the Notebook

```bash
jupyter lab
# or
jupyter notebook
```
Open `HeartFailurePrediction.ipynb` and run all cells.
