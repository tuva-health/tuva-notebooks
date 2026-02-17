# Tuva Notebooks

This repo contains a collection of jupyter notebooks that run on top of the Tuva data model.

## Open in Google Colab

Demo:
- https://colab.research.google.com/github/tuva-health/tuva-notebooks/blob/main/demo.ipynb

Algorithm for Grouping Claims into Encounters:
- https://colab.research.google.com/github/tuva-health/tuva-notebooks/blob/main/algorithm_for_grouping_claims_into_encounters.ipynb

ED Classification:
- https://colab.research.google.com/github/tuva-health/tuva-notebooks/blob/main/ed_classification.ipynb

## Run Notebooks Locally (Virtual Environment)

This repo includes a local virtual environment at `.venv` and a pinned `requirements.txt`.

Activate the environment and open a notebook:

```bash
cd tuva-notebooks
source .venv/bin/activate
jupyter notebook ed_classification.ipynb
```

## Recreate the Virtual Environment

If you need to recreate the environment from scratch:

```bash
cd tuva-notebooks
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
