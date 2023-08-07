# Pistachio_classification

## Table of contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Data Science Methodology](#data-science-methodology)
    - [Project Description](#project-description)
    - [Data Science Methods](#data-science-methods)
- [Conclusions](#conclusions)
- [Status and Details](#status-and-details)
- [Technology](#technology)

## Introduction
Did you know there are numerous varieties of pistachios? Considering that each species has unique properties, recognising and isolating pistachios is a highly practical technique. 
Some pistachios, for example, are better suited for baking, and others, which are more crunchy, are generally consumed as snacks.
Pistachio types detection, numbers are extracted by image processing methods.

### Objectives
- Gain a deeper understanding of estimators used in classification and hyper-parameter tuning. 
- Provide a visual representation of the data.
- The algorithm was designed to identify what pistachio type a pistachio belonged to using a feature vector based containing geometrical information. 

## Data Science Methodology

### Project Description
Correlation matrices, box plots, and histograms have been used to clearly visualise trends in the dataset. 
Classification models were trained on a large preprocessed dataset, yielding accurate results.
The model hyper-parameters were tuned using GridSearchCV which exhaustively considers all parameter combinations which give the best f1-score.
Receiver Operating Characteristic (ROC) curve was plotted along with a precision-recall curve and precision-recall tradeoff curves.


### Data Science Methods
- Data Preprocessing
- Data Visualisation
- Machine Learning
- Predictive Modelling
- Hyperparameter Tuning

## Conclusions
When using grid searches to optimise the hyperparameters for a k-nearest neighbours classifier, decision tree, and logistic regression, it was found that the k-nearest neighbours classifier had the best f1-score. 
The area under the ROC curve was found to be 0.93 which is indicative of a good classifier.

## Status and Details
- **Project Status**: [Completed]
- **Date Coded**: 01/08/23
- **Link to Raw Dataset**: https://www.kaggle.com/datasets/amirhosseinmirzaie/pistachio-types-detection
- **Notes**: This project was to gain a better understanding of different supervised learning techniques and hyperparameter tuning.

## Technology
- **Language**: Python 3.11.4
- **Libraries**: pandas, numpy, matplotlib, seaborn, scipy, sklearn
