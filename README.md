create env 

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
```

```bash
git init
```
```bash
dvc init 
```
```bash
dvc add data_given/winequality.csv
```
```bash
 git add . && git commit -m "first commit"

```
```bash
git remote add origin https://github.com/nik-vaibhav18/mlops_wine_quality.git
git branch -M main
git push origin main
```

to track the dvc 
```bash
dvc repro
```

1.  Firstly created params.yaml with parameter as config file
2.  Then created get_data, load_data and split data pyhton files
3.  Then simulataneously ttacke changes in dvc.yaml file and ran the command as ``` dvc repro```

to tack the metrics params and its performance below are followinbg commans
```bash
dvc metrics show
```

```bash
dvc metrics diff
```
tox command
```bash
tox
```
-- for rebuilding
```bash
tox -r
```
pytest command
```bash
pytest -v
```


to build packages of the program written

```bash
pip install -e .
```

```bash
python setup.py sdist bdist_wheel
```

