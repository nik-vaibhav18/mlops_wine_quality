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