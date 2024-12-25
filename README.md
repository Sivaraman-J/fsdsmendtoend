# This is my first End to End Project


# first initialize the git

```
git init
```

```
git add abc.txt

git add .
```

```
git commit -m "this is my first commit"
```

```
git pull

```

```
bash your_file_name.sh
```

```
python setup.py install
```

# another way you can mention -e . in your requirement file and you can run

```
pip install -r requirements.txt
```


```
MLflow
Documentation

local cmd
mlflow ui

dagshub

dagshub

MLFLOW_TRACKING_URI=https://dagshub.com/sivaramanperumal/fsdsmendtoend.mlflow
MLFLOW_TRACKING_USERNAME=sunny.savita
MLFLOW_TRACKING_PASSWORD=3c2c8cd1436ad32b510cfdd84944a528ba4fb650
python script.py

Run this to export as env variables:

export MLFLOW_TRACKING_URI=https://dagshub.com/sivaramanperumal/fsdsmendtoend.mlflow

export MLFLOW_TRACKING_USERNAME=sivaramanperumal

export MLFLOW_TRACKING_PASSWORD=3c2c8cd1436ad32b510cfdd84944a528ba4fb650
DVC cmd
dvc init
dvc repro
dvc dag


```






```
#MLflow Tracking remote:

https://dagshub.com/sivaramanperumal/fsdsmendtoend.mlflow



#Using Mlflow tracking

import dagshub
dagshub.init(repo_owner='sivaramanperumal', repo_name='fsdsmendtoend', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
```