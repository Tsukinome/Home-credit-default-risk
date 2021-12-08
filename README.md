# Credit

Files and notebooks for kaggle competition https://www.kaggle.com/c/home-credit-default-risk/overview
Notebook includes EDA, baseline modelling, feature engineering, merge of files and final modelling with various experiments such as hyperparameters optimization etc.

**Table of content:**
* [About](#about)
* [Technologies](#technologies)
* [License](#license)

### About
Competition is for solving binary classification task on loan repayment (1 - client with payment difficulties, 0 - all other cases). There are 7 different files and the main file contains information about applied person's gender, some possessions, family, occupancy, residence and application information such as weekday, time, provided documents, etc. Other files contain information from bureau, credit card, previous applications, and more.
Goal was to try out several different models and understand their principles, parameters and speed but the main focus was on modelling and scoring at kaggle.

### Technologies
* Python - version 3.8
* Jupyter Notebook
* Scikit-learn tools
* XGBClassifier
* RandomForestClassifier
* LGBMClassifier

### License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
