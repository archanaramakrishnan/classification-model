# Introduction to Data Science, Project 2: To be, or not to be
------------

## My Analysis
### Find my [jupyter notebook here](https://github.com/archanaramakrishnan/classification-model/blob/master/notebooks/ShakespeareClassification.ipynb).

I used data preparation and extraction to clean up the data and pick the lines that are active dialogs rather than passive actions. I used the naive bayes, decision tree and random forest classifiers and random forest gave me the best accuracy. I created a word coud visualization to depict the frequency of a player's lines in the dataset.

## Project Prompt
Classy Shakespeare plays and players

- Set up a data science project structure in a new git repository in your GitHub account
- Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays
- Load the data set into panda data frames
- Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
- Build one or more classification models to determine the player using the other columns as features
- Document your process and results
- Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   └── raw            <- The original, immutable data 
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── notebooks          <- Jupyter notebooks. 
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
