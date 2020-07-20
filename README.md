# Credit_Card_Fraud_Detection

# Project Aimed:
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. The aim of the project is that to detect fraud transaction if any. The context of the project is to help credit card companies recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.


# Pre-Requisites:
Python3 
Some of the Python Libraries
1.  numpy           "https://numpy.org/"
2.  pandas          "https://pypi.org/project/pandas/"
3.  seaborn         "https://pypi.org/project/seaborn/"
4.  sklearn         "https://pypi.org/project/sklearn/"
5.  matplotlib      "https://pypi.org/project/matplotlib/"
6.  nltk            "https://pypi.org/project/nltk/"
7.  re              "https://pypi.org/project/regex/"

# Installation:
There are some steps for installation
1.  Install Python3.                        "https://www.python.org/downloads/"
2.  Download and Install Anaconda Toolkit   "https://www.anaconda.com/products/individual"  
3.  Install Spyder.                         
4.  Install all the libraries above mentioned by using "pip install library_name".
5.  Download the project. Run it in your system.

# Dataset:
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.The dataset contains transactions made by credit card including fraud and real transactions both.Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Note: The dataset is downloaded from Kaggle: "https://www.kaggle.com/mlg-ulb/creditcardfraud/".

# Algorithm:
As the data is structured and after analyzing the dataset I came to know that we can use classifier in this project.In this seaborn library that uses matplotlib is used to plot graphs and pandas is used for reading the dataset.  
I am getting 78% accuracy in this project.

