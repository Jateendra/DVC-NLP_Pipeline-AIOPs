# DVC Architecture NLP pipeline AIOPs

## Reference repository :
[Reference repository](https://github.com/iterative/example-get-started)

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

OR
```bash
conda create -n dvc-nlp python=3.7 -y
source activate dvc-nlp
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository

### Special Commands
To ignore .logs files to be commited to github while comitting .
```bash
echo "*.logs" >> logs/.gitignore
```
To remove file from Github.
```bash
rm 'logs/running_logs.log'
```
