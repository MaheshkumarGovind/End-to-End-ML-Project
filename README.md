# End-to-End-ML-Project



# End-to-end-Machine-Learning-Project-with-MLflow


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/MaheshkumarGovind/End-to-End-ML-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.10 -y
```

```bash
conda activate mlproj
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



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

import dagshub
dagshub.init(repo_owner='MaheshkumarGovind', repo_name='End-to-End-ML-Project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/MaheshkumarGovind/End-to-End-ML-Project.mlflow

set MLFLOW_TRACKING_URI=https://dagshub.com/MaheshkumarGovind/End-to-End-ML-Project.mlflow

set MLFLOW_TRACKING_USERNAME=Mahesh Kumar

set TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0 

