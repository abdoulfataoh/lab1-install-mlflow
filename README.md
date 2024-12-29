### lab1-install-mlflow
This lab aims to guide you through setting up a Python virtual environment and installing MLflow to manage machine learning experiments and models.


#### 1. Create python project

```bash
mkdir mlflow-server && mv mlflow-server  # to create project && move to the the project

```

#### 2. Install python Virtual Env (If not)

```bash
pip install virtualenv
```

#### 3. Create a Virtual Env

```bash
virtualenv venv
```

> This will create a folder name `venv`


#### 4. Enable venv

- For Windows users

```bash
.\venv\Scripts\activate
```

- For MacOS/Linux users

```bash
source venv/bin/activate
```

#### 5. Install mlflow

```bash
pip install mlflow
```

#### 6. Run mlflow

```bash
mlflow server --host 127.0.0.1 --port 8000
```

#### 7. Check if everything works well

> Request from your browser the below @

```bash
http://localhost:8000
```

### References
[[1] https://mlflow.org/docs/latest/getting-started/intro-quickstart/index.html ](https://mlflow.org/docs/latest/getting-started/intro-quickstart/index.html)

[[2] Lab2 : Configure mlflow for machine learning experiments tracking](https://github.com/abdoulfataoh/lab2-configure-mlflow-for-exp-tracking)

