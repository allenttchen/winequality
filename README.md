# Wine Quality Pipeline

Make sure to install the required packages
```bash
pip install -r requirements.txt
```

MLFlow Command
```bash
mlflow server
--backend-store-uri sqlite:///mlflow.db
--default-artifact-root ./artifacts
--host 0.0.0.0 -p 1234
```