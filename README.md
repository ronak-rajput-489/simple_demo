create env
```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

create a recuirenmwnt file

install recuirenmwnt file
```bash
pip install -r recuirenment.txt
```

download the data set from

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
git commit -m "first commit....."
```

onliner update readme.md file
```bash
git add . && git commit -m "update README.md"
```
```bash
git remote add origin https://github.com/ronak-rajput-489/simple_demo.git
git branch -M main
git push -u origin main
```







