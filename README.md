# Kaggle - Titanic
This repo is for the Notebook in the Kaggle Titanic challenge.

## Pre-Requisites
- Python 3.6-3.8 (virtual env recommended)
- Pycaret 2.0 or greater

## Download Dataset

The following is already done in this repo, but instructions are below if a fresh dataset is needed.

Retrieve kaggle dataset. Refer to [kaggle's API documentation](https://github.com/Kaggle/kaggle-api) for details on how to install and access.

`kaggle competitions download -c titanic`

Unzip files to the data directory. Instructions for Powershell:

`Expand-Archive -LiteralPath titanic.zip -DestinationPath data`

## Submit to Kaggle
Once model is created, submit to Kaggle either through UI or via CLI.

`kaggle competitions submit -c titanic -f submission.csv -m "Message"`