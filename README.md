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
download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

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
git add .
```
```bash
git commit -m "first commit"
```
oneliner updates  for readme

```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add originhttps://github.com/swarnava-96/Wine-Quality--ML-OPS.git
git branch -M main
git push origin main
```


