# Test command

```
cd <PROJECT_DIR>
export MLFLOW_TRACKING_URI=databricks
mlflow run https://github.com/jjaiwant328/sklearn-mlflow  -b databricks --backend-config cluster-spec.json --experiment-id <experiment-id>
```

