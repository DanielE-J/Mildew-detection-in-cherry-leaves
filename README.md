# Mildew detection in cherry leaves

![Responsivity image](/assets/images/dashboard_responsivity.png)

## Table of Contents

- [Mildew detection in cherry leaves](#mildew-detection-in-cherry-leaves)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Dataset Content](#dataset-content)
  - [Business Requirements](#business-requirements)
  - [Hypothesis and validation](#hypothesis-and-validation)
    - [Hypothesis 1](#hypothesis-1)
    - [Hypothesis 1 Validation](#hypothesis-1-validation)
    - [Hypothesis 2](#hypothesis-2)
    - [Hypothesis 2 Validation](#hypothesis-2-validation)
    - [Hypothesis 3](#hypothesis-3)
    - [Hypothesis 3 Validation](#hypothesis-3-validation)

## Introduction

Mildew detection in cherry leaves is a data science and machine learning (ML) project that uses predictive analytics to tell the difference between 2 different sets of images. The business goal is to assist the client, an agri-food business who is dealing with an infestation of powdery mildew in its cherry tree leaves. 

Currently the client is inspecting trees manually to determine whether they are infected or not and then treated if found to be diseased. This process is both labour intensive and time consuming. We propose the creation of a ML model that can determine from photographs of leaves whether mildew is present, reducing the amount of time taken to determine the status of the tree and enable sick trees to be treated with greater efficiency and accuracy. 

The project is hosted on the streamlit app and a live version may be found [here](https://cherrypowderymildewdetector-eb00906f7030.herokuapp.com/)


## Dataset Content

- The dataset is sourced from [Kaggle](https://www.kaggle.com/codeinstitute/cherry-leaves). We then created a fictitious user story where predictive analytics can be applied in a real project in the workplace.
- The dataset contains +4 thousand images taken from the client's crop fields. The images show healthy cherry leaves and cherry leaves that have powdery mildew, a fungal disease that affects many plant species. The cherry plantation crop is one of the finest products in their portfolio, and the company is concerned about supplying the market with a compromised quality product.

## Business Requirements

The cherry plantation crop from Farmy & Foods is facing a challenge where their cherry plantations have been presenting powdery mildew. Currently, the process is manual verification if a given cherry tree contains powdery mildew. An employee spends around 30 minutes in each tree, taking a few samples of tree leaves and verifying visually if the leaf tree is healthy or has powdery mildew. If there is powdery mildew, the employee applies a specific compound to kill the fungus. The time spent applying this compound is 1 minute. The company has thousands of cherry trees located on multiple farms across the country. As a result, this manual process is not scalable due to the time spent in the manual process inspection.

To save time in this process, the IT team suggested an ML system that detects instantly, using a leaf tree image, if it is healthy or has powdery mildew. A similar manual process is in place for other crops for detecting pests, and if this initiative is successful, there is a realistic chance to replicate this project for all other crops. The dataset is a collection of cherry leaf images provided by Farmy & Foods, taken from their crops.

- 1 - The client is interested in conducting a study to visually differentiate a healthy cherry leaf from one with powdery mildew.
- 2 - The client is interested in predicting if a cherry leaf is healthy or contains powdery mildew.

## Hypothesis and validation

### Hypothesis 1

 Infected leaves exhibit visible discoloration, spots, or deformities that are not present on healthy leaves.

### Hypothesis 1 Validation

 Research about the disease and build an image study that can help to investigate it.<br/>

### Hypothesis 2

  The softmax activation function yields superior performance compared to the sigmoid activation function when used in the output layer of a Convolutional Neural Network (CNN).

### Hypothesis 2 Validation

 Identify the problem type and the mathematical properties of each activation function. Train identical CNN models differing only in the output activation (softmax vs. sigmoid), then compare their performance using appropriate evaluation metrics.

### Hypothesis 3

 Model accuracy is influenced by the output layer’s activation function. Our initial study used a sigmoid for binary classification of healthy vs. diseased leaves. We now propose using softmax for multi-class classification, which we expect to reduce accuracy.
 
### Hypothesis 3 Validation

 We validated this by creating a final version of the ML model. This time, when augmenting the dataset the class mode was changed to categorical and the activation function in the ML model was changed to softmax.
