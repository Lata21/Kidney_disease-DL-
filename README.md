# Kidney-Disease-Classification-MLflow-DVC

# How to run?
### STEPS:

Clone the repository   https://github.com/Lata21/Kidney_disease-DL-.git
```
###STEP 01- Create a conda environment after opening the repository

```bash
python -m venv newwnv
```

```bash
newenv/bin/activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

##### cmd
- mlflow ui

# dagshub 
MLFLOW_TRACKING_URI="https://dagshub.com/username/repositoryname"


MLFLOW_TRACKING_USERNAME="xxxxxxxxxxx"

MLFLOW_TRACKING_PASSWORD = "xxxxxxxxxxxxxxxx"

python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=  https://dagshub.com/username/repositoryname

export MLFLOW_TRACKING_USERNAME= "XXXXXXX"

export MLFLOW_TRACKING_PASSWORD = "XXXXXXXXXXXXXXXXXXXXXXXXx"

```


# DVC cmd

1. dvc init
2. dvc repro
3. dvc dag



# Machine Learning Tools Overview

## MLflow
MLflow is a **production-grade** platform for managing the ML lifecycle, offering:

- **Experiment Tracking**: Record parameters, metrics, and artifacts for reproducibility.
- **Model Logging & Tagging**: Log and organize models with version control.
- **Model Registry**: Centralized storage and deployment for models.
- **Deployment & Integration**: Easily deploy models to production and integrate with major platforms.
- **Scalability**: Ideal for large-scale enterprise projects.

## DVC (Data Version Control)
DVC is a **lightweight** tool for versioning and orchestrating ML workflows, perfect for small-scale projects:

- **Experiment Tracking**: Track experiments with a simple interface.
- **Pipeline Orchestration**: Create reproducible ML pipelines.
- **Data Versioning**: Version datasets and models efficiently.
- **Cloud Support**: Integrates with cloud storage like AWS S3, Google Drive.
- **Collaboration**: Share versioned data and models with teams.

