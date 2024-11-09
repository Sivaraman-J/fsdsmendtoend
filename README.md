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