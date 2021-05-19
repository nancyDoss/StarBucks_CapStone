# StarBucks_CapStone
The scope of this project is to analyse the 3 different dataset of the user from Starbucks. 
The process involved in this project is covers all the traits of the Data Science.

* Data Mining
* Data Wrangling
* Data Visualisation
* Data Cleaning
* Data Proceessing using ML
* Analysing the Data

## Table of Contents
1. Libraries
2. Data Blog
3. File Descriptions
4. Results
5. Reference

### Libraries
This project uses lot of libraries if its not already installed, kindly install it prior to use.
This project executed entirely in Python 3, so not tested in python2.
List of all the libraries used, is listed down for reference.

```python
import pandas as pd
import numpy as np
import math
import json
from sklearn import model_selection
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
from sklearn.naive_bayes import GaussianNB
from sklearn.svm import SVC
from sklearn.model_selection import train_test_split
% matplotlib inline
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import KFold
from sklearn.model_selection import StratifiedKFold
from sklearn.model_selection import cross_val_score
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import classification_report
from sklearn.metrics import confusion_matrix
from sklearn.metrics import accuracy_score
from sklearn.pipeline import Pipeline
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
from sklearn.naive_bayes import GaussianNB
from sklearn.svm import SVC
from sklearn.ensemble import AdaBoostClassifier
from sklearn.ensemble import GradientBoostingClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import ExtraTreesClassifier
```

### Data Blog
The link will take you to the data blog, that is written for technical audience, that has the detailed 
analysis with the visualisation explain.


### File Descriptions
a. starbuck_notebook.ipynb : Jupyter notebook
b. Data Sets
The data is contained in three files:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed
Here is the schema and explanation of each variable in the files:

1. portfolio.json

* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

2. profile.json

* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

3. transcript.json

* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record



### Results


### Reference
* reference from kaggle for [ML](https://www.kaggle.com/pouryaayria/a-complete-ml-pipeline-tutorial-acu-86)
* reference for [markdown](https://medium.com/@saumya.ranjan/how-to-write-a-readme-md-file-markdown-file-20cb7cbcd6f)
* 
