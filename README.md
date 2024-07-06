# machine-learning-module2lab
Module 2 Lab
Melissa Stone Rogers, July 5, 2024

## Introduction
Professional project to use Jupyter Lab, python, and needed frameworks to prepare Howell dataset for machine learning.
Commands were used on a Mac machine running zsh.  

## How to Install and Run the Project
Create project repository in Github and clone to your machine.

```
git clone project.url
```
Verify Python version of Python 3
```
python3 --version

```
```
python3 -m venv ds-venv
source ds-venv/bin/activate
```

Install required packages 
```
pip install jupyterlab pandas
python3 -m pip install -U scikit-learn
```

Create requirements.txt in the root project folder. 
```
touch requirements.txt
```
Add the following requirements into requirements.txt:
- jupyterlab 
- pandas

## Freeze Requirements

```
python3 -m pip freeze > requirements.txt
```

## Add .gitignore File
Add .gitignore file to the root project folder. 
```
touch .gitignore
```
Add the following to your .gitignore file: 
- .ds-venv/
- .vscode/
- .ipynb_checkpoints/

## Initial Project Save
```
git add .
git commit -m "initial"                         
git push origin main
```
### Start and Complete Project 
Copy lab1_starter.ipynb into workspace and open it. 

Follow project steps as found in [this PDF](https://github.com/meldstonerogers/machine-learning-module1lab/blob/main/Lab%20W1%20scikit.pdf).
