### How to create a conda environment

```
conda create -n mlops-LR python=3.7 -y
```

### Activate the conda environment

```
conda activate mlops-LR
```

### Install the required libraries/packages

```
pip install -r requirements.txt
```

### To check the ML pipelines are working

```
dvc repro
```

### To check the metrics

```
dvc metrics show
```

### To invoke the service

```
python app.py
```
#### NOTE : Data is being stored at Google Drive Through DVC.
