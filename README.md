# Machine Learning and Statistics 

* **Author:** Richard Deegan
* **Github:** Deego88
* **Email:** G00387896@gmit.ie
* **Lecturer:** Ian McLoughlin
------------------------------------------------------------------------------------------------
**Machine Learning and Statistics:** 

This Jupyter Notebook has been created to answer the assignment requirements available [here](https://github.com/Deego88/MLS) 

The full Project instructions can be found [here](https://github.com/Deego88/MLS) 


**Table of Contents**
------------------------------------------------------------------------------------------------

[Project - Machine Learning and Statistics s](#Assignment- Project-Machine-Learning-and-Statistics)

[1. Introduction](#1-introduction)

[2. Project Repository](#2-project-repository)

[3. Overview](#3-Overview)

[4. Problem Statement](#4-Problem-Statement)

[5. User Guide](#5-User-Guide)

  [5.1 Downloading the Repository](#5.1-Downloading-the-Repository)

  [5.2  Running the Program](#5.2-Running-the-Program)

  [5.3  Libraries](#5.3-Libraries)

[6. References](#7-References)


## 1 Introduction
-----------------------------------------------------------------------------------------------
This assignment project uses Python, Jupyter, SciPy, and Anova.  This project is conducetd as part of the Machine Learning and Statistics module of the Higher Diploma in Data Analytics at GMIT.

The Scipy-Stats Jupyter notebook contains a fake random data set obtained from Numpy.random.
The Scikit-Learn Jupyter notebook contains a CSV data set imported from Kaggle.com on the Indians Diabetes Database [13].
These data sets are used to conduct analysis and to produce visual representations and draw conclusions.

## 2 Project Repository
------------------------------------------------------------------------------------------------
The project repository is the source where all the work associated with
the project will be stored. It contains the following files and can be
located [here](https://github.com/Deego88/MLS):

  **File**    |     **Description**
  ---------   |   --------------------------------------------------------
  .gitignore | A Text File explicitly explaining to Git which files or folders to ignore in the Assignment
  Assessment_Instructions.pdf | A PDF copy of the Poject Instructions
  LICENSE     |    MIT License for the project
  Scikit-learn.ipynb | Jupyter Notebook created in Python
  Scipy-stats.inpb | Jupyter Notebook created  in Python
  README.md   |    This file; A Description of the project and instructions
  diabetes.csv   |    This file contains information used to conduct analysis for the project


## 3  Overview
------------------------------------------------------------------------------------------------
 For the purpose of this project the author chose the following:
 
Scikit-Learn:
1. K-Nearest Neighbors
2. K-Means Clustering
3. Logistic Regression 

Scipy-Stats:
1. ANOVA Hypothesis 
2. ANOVA Assumptions
3. Visual displays


## 4 Problem Statement
------------------------------------------------------------------------------------------------
As part of the project, the student was given a set of instructions, the full set can be see here [here](https://github.com/Deego88/MLS). In short, the instructions of the project state the following:
The purpose of this assessment is to ensure that the student has achieved the learning outcomes
of the module while also providing teh student with sample work to show prospective
employers. 

The project assessment is split into the three components:

1. GitHub Repository

2. Scikit-Learn Jupyter Notebook

3. Scipy Stats Jupyter Notebook

## 5 User Guide
------------------------------------------------------------------------------------------------
This section will describe the steps required to download and run the files in the repository.

### 5.1 Downloading the Repository
The repository is stored at the following: https://github.com/Deego88/MLS

To download the repository, do the following:
1.  Click on the above link to open the repository
2.  Once in the repository, click on the green ???clone or download??? button on the right side of the screen.
3.  Select "Download ZIP". This will open a prompt allowing you to save the file to a desired location on your computer.
4.  Navigate to where  the ZIP files are located on your computer and extract the compressed (.zip) files.

### 5.2 Running the Program
Once the repository has been downloaded, you will need to ensure that you are running it in the correct environment. It should be noted that this repository has been written using Python 3.8.2 and consequently it will require a Python version of 3.7 at a minimum to run as designed. The repository also requires a number of external Python libraries [seen below](#5.3-Libaries) to execute correctly. Once the correct version of Python has been installed complete with necessary libraries and the ZIP has been downloaded and extracted the user can run the program. The running of any of the programs from the command line can be executed as follows:
1.  Open a command prompt (cmd) or equivalent on your computer.([Cmdr](https://cmder.net) is recommended for Windows computers, Mac Computers via the terminal)
2.  Navigate to the desired location through the use of the change directory (cd) command.
3. Run Jupyter Notebook by typing the following at the command prompt (do not close the command prompt window throughout):
```
jupyter notebook
```
4. A notebook server should automatically launch in your default web browser (URL should be http://localhost:8888). If this does not happen, read the command prompt output. You can copy and paste the above URL into your web browser to access Jupyter Notebook.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
```
Scipy-stats.ipynb
Scikit-learn.ipynb
```
7. The notebooks should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.

### 5.3 Libraries
The following Python libraries were used in the writing of the projects code and are required to successfully run the programs:

-import numpy as np
-import pandas as pd
-import matplotlib.pyplot as plt
-import seaborn as sns
-scikit-learn
  -from sklearn.preprocessing import StandardScaler, LabelEncoder
  -from sklearn.model_selection import train_test_split
  -from sklearn.neighbors import KNeighborsClassifier
  -from sklearn.metrics import classification_report, confusion_matrix
  -from sklearn import linear_model
  -from sklearn.linear_model import LogisticRegression
  -from sklearn import metrics
  -from sklearn.cluster import KMeans
  -from sklearn.metrics import accuracy_score, roc_auc_score, roc_curve
  -from sklearn import datasets
-scipy.stats
  -from scipy.stats import norm
  -from scipy.stats import uniform
  -from scipy.stats import binom
  -from scipy import stats
  -from scipy.stats import f 
  -from statsmodels.formula.api import ols
  -from scipy.stats import bartlett
  -from scipy.stats import levene
-Anova

## 6 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.
