# ML Project - Logistic Regression Experiments

This repository contains simple Logistic Regression experiments and notebooks used for learning and comparing manual implementations vs scikit-learn.

## Content

- `data.csv` — dataset used by the notebooks.
- `Manual LR.ipynb` — notebook with a manual implementation of logistic regression.
- `SKlearn LR.ipynb` — notebook using scikit-learn's logistic regression.

## Setup

1. Create and activate a virtual environment (Windows PowerShell example):

```
python -m venv venv
Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
& "venv\Scripts\Activate.ps1"
```

2. Install common dependencies:

```
pip install -U pip
pip install pandas numpy scikit-learn matplotlib jupyter
```

(Optionally create a `requirements.txt` with these packages.)

## Usage

- Open the notebooks with Jupyter Lab or Notebook:

```
jupyter notebook
```

- Run cells in `Manual LR.ipynb` and `SKlearn LR.ipynb` to reproduce experiments.

## Notes

- The notebooks expect `data.csv` in the repository root.
- If you want, I can add a `requirements.txt` and a small `run.sh`/`run.ps1` helper.

## Author

Project workspace: `d:\projects\Ml Project\my project and friends`
