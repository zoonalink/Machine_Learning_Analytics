# Machine Learning

## Assessing Machine Learning Models for Predicting Student Outcomes form Engagement Data

## Description

This repository contains files associated with a report submitted as assessed coursework for *Machine Learning and Predictive Analytics - [UFCFMJ-15-M](https://www.cems.uwe.ac.uk/~h-ihshaish/ml/assignment/)* at the [University of the West of England, Bristol](https://www.uwe.ac.uk/).  

## Abstract

Higher Education Institutions (HEI) have a vested interest in ensuring that students are successful in their studies.  The motivation is multi-faceted - ensuring a positive student experience and good student outcomes, HEIs reap the benefits of a good reputation and are able to attract more students.  HEIs are also subject to external scrutiny in the form of statutory reporting requirements and league table placement.  

Learner Analytics is a field of research which can be used to support students and HEIs by improving student experience, improving learning and teaching, identifying at-risk students, and improving retention and progression.

This is an exploratory report which investigates predictive learning algorithms trained on student engagement data to predict outcomes.  It is proof-of-concept in nature, exploring the viability and generalisability of learning algorithms on engagement behaviour during a course.  It compares several models and briefly discusses the results in the context of the HEI.

The [Open University Learning Analytics dataset](https://analyse.kmi.open.ac.uk/open_dataset) is used to train, validate and test classification learner models.

## How to use this repository

This repository has **not** been prepared for general use.  It is a repository of working files and notebooks which were used to produce the report.  Notebooks contain code, commentary, thoughts and ideas.  

They are not intended to be read as a narrative, although they are referenced in the report and supply additional information.

It is my intention to keep working on some of the findings and additional research questions.

As such, the code is presented as-is with no guarantees.

## Requirements

All code was written in Python 3.11.0.

The following packages are required:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* additional packages may be required

### More details

[data](/data/) folder contains the data used in the report as well as generated files
[coursework](/coursework/) folder contains the ipython notebook used to generate the report in Word format

* there **will** be minor variations between the Word Document and the ipython file
* the ipython file does not contain any code
[code](/code/) folder contains various ipython notebooks used to explore the data and generate the report
* [V1](/code/V1/) folder contains the first version of my code
  * notebooks are named in the order they were created / used
  * some code needs to be updated to function properly
* [V2](/code/V2/) folder contains the second version of my code
  * notebooks are named in the order they are meant to be read
  * these notebooks are more complete and more in line with the report content

[V2/00_data_description](/code/V2/00_data_description.ipynb) contains a description of the data used in the report
[V2/00_introduction](/code/V2/00_introduction.ipynb) contains the introduction to the report
[V2/01_data.ipynb](/code/V2/01_data.ipynb) contains initial data exploration
[V2/02_EDA.ipynb](/code/V2/02_EDA.ipynb) contains exploratory data analysis
[V2/03_Features.ipynb](/code/V2/03_Features.ipynb) contains feature engineering code and narrative
[V2/04_01_model_prep.ipynb](/code/V2/04_01_model_prep.ipynb) contains code to prepare data for modelling
[V2/04_02_model_reduce.ipynb](/code/V2/04_02_model_reduce.ipynb) contains code to reduce the number of features and feature space (PCA)
[v2/04_03_model_fit.ipynb](/code/V2/04_03_model_fit.ipynb) contains code to fit models
[V2/04_04_model_tune.ipynb](/code/V2/04_04_model_tune.ipynb) contains code to tune models
[V2/04_05_model_test.ipynb](/code/V2/04_05_model_test.ipynb) contains code to prepare test scenario
[V2/04_06_model_test_model.ipynb](/code/V2/04_06_model_test_model.ipynb) contains code to test model on 50/100/150 test sets


## Assignment Specification / Brief

[Full Assignment Specification](https://www.cems.uwe.ac.uk/~h-ihshaish/ml/assignment/)

Your report (in a form of a discussion paper) should cover the following points:

* Discuss a machine learning problem given your chosen application; identify the prob-lem, the requirements for a predictive model and its impact.
* Describe and analysis a dataset and its characteristics; size, representation and at-tributes,
* Discuss whether bivariate or multivariate analysis is most suitable for your predictive model.
* Choose/apply (a) learning algorithm(s) and identify its/their categories; supervised, un-supervised, semi-supervised.  
* Analytically evaluate your choice of machine learning solution; its suitability, cost, and apply an error evaluation metric to justify your choice, e.g., classification accuracy of classification problems, MSE and/or R^2 (R squared) for regression models, etc.  
* Choose a learning algorithm which you think is less suitable for your predictive model and justify your “rejection” reasons.
