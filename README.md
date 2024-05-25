ML Flow experiment with wine quality dataset

import dagshub
dagshub.init(repo_owner='mns.she', repo_name='mlflow_wine_krish', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
