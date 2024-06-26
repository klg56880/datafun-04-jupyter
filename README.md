# datafun-04-jupyter
Module 4 project

## How to Install and Run the Project

## Create project
Created a new repo in GitHub with the name 'datafun-04-jupyter' 

Added the default README.md 

Named the script karitaylor_eda.ipynb_

## Clone project down to my machine
Opened VS Code 

Used file > open folder to access the folder where I want my project to reside

Opened a new terminal (with powershell as default) 

Used the 'git clone' command to clone the project to my machine

```shell

git clone site_URL

```

## Create a requirements.txt file
Created a new file in my datafun-04-jupyter folder labeled requirements.txt

## Create and activate a Python virtual environment
Used the following command to create a virtual environment:
```shell

py -m venv .venv

```
Used the following command to activate the virtual environment:
```shell

.\.venv\Scripts\Activate.ps1

```

## Install dependencies in the requirements.txt file and freeze
Installed dependencies using the following command:
```shell

py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy

```
Froze the requirements.txt file using the following command:
```shell

py -m pip freeze > requirements.txt

```

## Create .gitignore
Created a new file in my datafun-04-jupyter folder named .gitignore

Typed .venv/ into line 1

## Git add and commit changes
Git add and commit my initial changes with the following commands:
```shell

git add .
git commit -m "initial commit"

```

## Git push changes to GitHub
Git push your initial changes to GitHub with the following command:
```shell

git push origin main

```

## Repeated Git add and commit
Periodically add, commit, and push files from my machine to the associated online repo using the following commands:
```shell

git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main

```

## Created Jupyter Notebook according to the following specifications:
[datafun-04-spec](https://github.com/denisecase/datafun-04-spec?tab=readme-ov-file)
