create Environment
 ```bash
    conda create - n wineq python=3.7 -y
 ```

activate env
 ```bash
    conda activate wineq
 ```

create requirement file


install requirements from requirement file
    ```bash
    pip install -r requirements.txt
    ```

download dataset from:

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

```bash
    git init

    dvc init

    dvc add data_given/winequality.csv

    git add .

    git commit -m "First commit"
```

tox command: 
```bash
    tox
```
to rebuild:
```bash
    tox -r
```

pytest command:
```bash
    pytest -v
```
setup commands:
```bash
    pip install -e .
```

Building the package:
```bash
    python setup.py sdist bdist_wheel
```
