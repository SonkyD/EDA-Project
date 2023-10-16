# EDA Project
### This Repo Contains:
- CSV containing the used dataset
- Jupyter Notebook containing the actual EDA Project
- assignment.md explaining our given task
- column_names.md explaining the data
- This readme.md
- requirements.txt showing the required settings
### Usage of EDA Project October 2023
- if connected to Database ds-sql-playground:
All cells shall be executed once in consecutive order
- if not connected to data base: All cells shall be executed once in consecutive order, excluding the second one which is starting with the comment: #Import of Data via SQL
### Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.
In order to install the environment you can use the following commands:
```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
Created by: David Marks and Hannes Wecker in October 2023 for Neue Fische Data Science Bootcamp EDA Project

