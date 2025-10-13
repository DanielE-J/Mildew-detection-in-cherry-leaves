![Banner]()

## Table of contents

1. [Introduction](#introduction)
2. [Dataset Content](#dataset-content)
3. [Business Requirements](#business-requirements)
4. [Hypotheses and validation](#hypotheses)
    1. [Hypothesis 1](#hypothesis-1)
    2. [Hypothesis 1 Validation](#hypothesis-1-validation)
    3. [Hypothesis 2](#hypothesis-2)
    4. [Hypothesis 2 Validation](#hypothesis-2-validation)
    5. [Hypothesis 3](#hypothesis-3)
    6. [Hypothesis 3 Validation](#hypothesis-3-validation)
5. [The rationale to map the business requirements to the Data Visualisations and ML tasks](#the-rationale-to-map-the-business-requirements-to-the-Data-Visualisations-and-ML-tasks)
6. [ML business case](#ml-business-case)
7. [Dashboard Design](#dashboard-design)
8. [Unfixed Bugs](#unfixed-bugs)
9. [Deployment](#deployment)
    1. [Heroku](#heroku)
10. [Main Data Analysis and Machine Learning Libraries](#main-data-analysis-and-machine-learning-libraries)
11. [Other technologies used](#other-technologies-used)
12. [Issues](#issues)
13. [Testing](#testing)
    1. [Manual Testing](#manual-testing)
    2. [Python Validation](#python-validation)
14. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)
15. [Acknowledgements](#acknowledgements)


## Introduction

Mildew detection in cherry leaves is a data science and machine learning (ML) project that uses predictive analytics to tell the difference between 2 different sets of images. The business goal is to assist the client, an agri-food business who is dealing with an infestation of powdery mildew in its cherry tree plantations. 

Currently the client is inspecting trees manually to determine whether they are infected or not and then treated if found to be diseased. This process is both labour intensive and time consuming. We propose the creation of a ML model that can determine from photographs of leaves whether mildew is present, reducing the amount of time taken to determine the status of the tree and enable sick trees to be treated with greater efficiency and accuracy. 

The project is hosted on the streamlit app and a live version may be found [here](https://cherrypowderymildewdetector-eb00906f7030.herokuapp.com/)