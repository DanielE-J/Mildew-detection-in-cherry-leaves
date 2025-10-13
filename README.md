![Banner]()

## Table of contents

- [Table of contents](#table-of-contents)
- [Introduction](#introduction)
- [Dataset Content](#dataset-content)
- [Business Requirements](#business-requirements)
- [Hypotheses](#hypotheses)
  - [Hypothesis 1](#hypothesis-1)
  - [Hypothesis 1 Validation](#hypothesis-1-validation)
  - [Hypothesis 2](#hypothesis-2)
  - [Hypothesis 2 Validation](#hypothesis-2-validation)
  - [Hypothesis 3](#hypothesis-3)
  - [Hypothesis 3 Validation](#hypothesis-3-validation)


## Introduction

Mildew detection in cherry leaves is a data science and machine learning (ML) project that uses predictive analytics to tell the difference between 2 different sets of images. The business goal is to assist the client, an agri-food business who is dealing with an infestation of powdery mildew in its cherry tree plantations. 

Currently the client is inspecting trees manually to determine whether they are infected or not and then treated if found to be diseased. This process is both labour intensive and time consuming. We propose the creation of a ML model that can determine from photographs of leaves whether mildew is present, reducing the amount of time taken to determine the status of the tree and enable sick trees to be treated with greater efficiency and accuracy. 

The project is hosted on the streamlit app and a live version may be found [here](https://cherrypowderymildewdetector-eb00906f7030.herokuapp.com/)


## Dataset Content

- The dataset is sourced from [Kaggle](https://www.kaggle.com/codeinstitute/cherry-leaves). 
- - The dataset contains over 4 thousand images taken from the client's cherry tree plantations. The images are divided into 2 sets, one of healthy leaves and one of leaves that are infected with powdery mildew. a fungal disease that affects many plant species. The client is concerned that the outbreak may be compromising the quality of their crop, which in turn would have serious ramifications for their business at large. 

[Back to top](#table-of-contents)

## Business Requirements

This project's main objective is to create a machine learning model that can detect whether a given tree has powdery mildew or not based on photographs uploaded to the dashboard as opposed to manual inspections of each tree, reducing costs in time and labour. This will result in more effective treatment and prevent a decline in crop quality. 

Key stakeholders for this are Farmy & Foods themselves, and their customers.

When considering the business requirements and how to meet them, attention must be paid to the following:

* The ML model produced must be accurate in its predictions of whether a leaf is infected or not
* The model should be able to handle multiple items concurrently
* The results produced from uploads must be easy to understand for both technical and non-technical personnel.
* The model must be able to return a prediction quickly

The specific requirements are as follows:

1. The client is interested in conducting a study to visually differentiate a healthy cherry leaf from one with powdery mildew. This should provide average images of both kinds of leaves, as well as a variability image for each.
2. The client is interested in predicting if a cherry leaf is healthy or contains powdery mildew. To meet this requirement, a Convolutional Neural Network (CNN) should be developed to classify images as healthy or infected.

[Back to top](#table-of-contents)

## Hypotheses

### Hypothesis 1

Infected leaves exhibit visible discoloration, spots, or deformities that are not present on healthy leaves.

### Hypothesis 1 Validation

### Hypothesis 2

The softmax activation function yields superior performance compared to the sigmoid activation function when used in the output layer of a Convolutional Neural Network (CNN).

### Hypothesis 2 Validation

### Hypothesis 3

Model accuracy is influenced by the output layer’s activation function. Our initial study used a sigmoid for binary classification of healthy vs. diseased leaves. We now propose using softmax for multi-class classification, which we expect to reduce accuracy.

### Hypothesis 3 Validation