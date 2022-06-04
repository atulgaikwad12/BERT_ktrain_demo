# BERT-k-train-usecase
Text Classification use case using BERT base architecture and fine tunning the model with the help of ktrain.
Dataset used - 20newsgroups dataset.


### Project Execution steps 
#### Clone repository in local
```bash
git clone <repository_url>
``` 
#### Execute below commands in git bash. (Note - Must have conda installed and path defined of conda in system environments)
##### Step 1 : Activate base conda Enviroment
`If using git bash then use below command`
```buildoutcfg
source activate base
```
`Else for cmd use`
```
conda activate base
```

##### Step 2 : Create new Conda Enviroment & Activate it
`To Create Conda Enviroment and activate it` 
```buildoutcfg
conda create -n <envName> python=3.7 -y
conda env list
activate <envName>
```

`Conda command to create virtual env inside current directly`
```
conda create --prefix ./env python=3.7 -y && conda activate ./env
```
##### Step 3 : Install required packages and List down libraries
```bash
pip install -r requirements.txt
conda list
```
##### Step 4 : To save your version of code. Create new git repository & then execute below commands only once to push change first time.
```bash
git add .
git status
git commit -m "commit message"
git remote add origin 'your_repository_url'
git branch -m master main
git push -u origin main
```
##### After first commit for subsequent changes just execute below commands
```bash
git add .
git commit -m "commit message"
git push
``` 
## To freeze new requirements.txt File
```buildoutcfg
pip freeze>requirements.txt
```
