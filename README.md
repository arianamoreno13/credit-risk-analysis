Description:

First we imported the imbalanced-learn library sklearn.metrics. We then use a logistic regression model to compare two versions of the dataset. First, we use the original dataset. Second, we resample the data by using the RandomOverSampler module from the imbalanced-learn library.

For both cases, we got the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.


This project uses python 3.7 with the following packages:

[pandas](Data analysis in Python with pandas/toc.txt) - For data analysis and manipulation.

[pathlib] - For interacting with file systems easier.

[sklearn.metrics import balanced_accuracy_score] - The balanced accuracy in binary and multiclass classification problems to deal with imbalanced datasets. It is defined as the average of recall obtained on each class.

[sklearn.metrics import confusion_matrix] - Compute confusion matrix to evaluate the accuracy of a classification.

[imblearn.metrics import classification_report_imbalanced] - Build a classification report based on metrics used with imbalanced dataset

[warnings.filterwarnings('ignore')] - to ignore the warning signals the code may encounter. 


Installation Guide: Before running the application first install the following dependencies:

import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')

Usage: This project allows us to identify the credit worthiness of people wanting to recieve loans. 

Contributors: brought to you by ~ Ariana Moreno Linkedin-[www.linkedin.com/in/ariana-moreno-52b2b7211]

License: MIT