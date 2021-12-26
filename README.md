# Machine-Learning-and-Statistics-Assessment

Jupyter Notebook focused repository, contains two primary notebooks for exploring different packages and interacting with them.

The aim of this repository is to demonstrate an understanding of both the sklearn and scipy.stats packages.
For sklearn an overview will be given to introduce sklearn as well as some other interesting aspects important to modelling like feature selection and cross-validation. Following this 3 different algorithms will be explored using different datasets.

In the SciPy notebook it will similarly introduce scipy.stats by giving a brief overview, and then getting into specifics will start to perform some ANOVA analysis on a suitable dataset.

Quick jump to section:
* [Contents of repository](#contents-of-repository)
* [Binder Hosting of Repository](#binder-hosting-of-repository)
* [Running the notebooks - Prerequisites](#running-the-notebooks---prerequisites)
* [scikit-learn notebook (scikit-learn.ipynb)](#scikit-learn-notebook-scikit-learnipynb)
* [SciPy Stats notebook (scipy-stats.ipynb)](#scipy-stats-notebook-scipy-statsipynb)

## Contents of repository:
* scikit-Learn.ipynb - notebook focused on the use of the scikit-learn package.
* scipy-stats.ipynb - notebook focused on the use of the scipy packages and it's stats module.
* requirements.txt - text file listing required packages.
* assessment.pdf - the project brief this repository is based on.
* .gitignore - file that tracks foldedrs, files and types of files to exclude from git.

## Binder Hosting of Repository
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/itskeithstudent/Machine-Learning-and-Statistics-Assessment/HEAD?labpath=scikit-learn.ipynb)

The notebooks in this repository are hosted over on binder which can be accessed using the above badge or by following this [link](https://mybinder.org/v2/gh/itskeithstudent/Machine-Learning-and-Statistics-Assessment/HEAD?labpath=scikit-learn.ipynb).

Binder gives a way to deploy jupyter notebooks within a git repository so that others can access your work, one of the issues that I encountered when deploying to binder was certain packages needed to be removed from requirements.txt that were specific to a windows environment, whereas binder uses a linux based operating system.


## Running the notebooks - Prerequisites
To run the notebooks they will require a few packages, to install these run the following command (preferably within a virtual environment):
 ```
 pip install -r requirements.txt
 ```
 Note: if not using conda you will need to do some additional set up to set up a kernel pointing to your virtual environment.
 
Each of the notebooks should be ran top to bottom sequentially, as subsequent cells may rely on variables being declared in an earlier cell or for a package to be imported, similarly there may be variable names which are re-used and so to ensure things are operating as intended be sure to run cells sequentially.
 
 ## scikit-learn notebook (scikit-learn.ipynb)
 This is a notebook which introduces and provides an overview of the sklearn package, it explores three different models across two different datasets.
 * Lasso Regression on California housing data
 * K Nearest Neighbours on Breast cancer dataset
 * Random Forest Classifier on same Breast cancer dataset
Throughout the different sections, observations are made as to what has been attempted, what the output means and what will be tried next as well as some conclusions of work done.

## SciPy Stats notebook (scipy-stats.ipynb)
This is a notebook which introduces and provides an overview of SciPy's stats package (scipy.stats), it explores an ANOVA analysis on a wine dataset, including verifying the different assumptions.
As the actual ANOVA analysis itself is fairly short, each feature in the dataset for the independent variables is evaluated to see whether it meets assumptions required for ANOVA.


 
