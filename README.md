# Kidney-Disease-Classification

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/AzizKorbi/Kidney-Disease-Classification/tree/main
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/AzizKorbi/Kidney-Disease-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=AzizKorbi \
MLFLOW_TRACKING_PASSWORD=5f77627c20b6fd4a3554a071d61ce51a044afb10 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/AzizKorbi/Kidney-Disease-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=AzizKorbi 

export MLFLOW_TRACKING_PASSWORD=5f77627c20b6fd4a3554a071d61ce51a044afb10

```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)
