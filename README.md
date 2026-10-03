# Student-Resource-3---Machine-Learning-Replication
# MACHINE LEARNING – STUDENT RESOURCE 3

## Project Description

This project is based on **Student Resource 3** from the Machine Learning module.

The resource contains **Version 1** and **Version 2**. I worked through both versions and repeated the practical steps using Python.

The main topic covered in this resource is **feature selection**. Feature selection is the process of choosing the most useful features from a dataset for a machine learning model.

The project uses two different datasets and shows different ways of selecting features and checking their effect on a machine learning model.
<img width="1325" height="579" alt="image" src="https://github.com/user-attachments/assets/8fd0ceab-c530-41e0-9847-8b6283f5d285" />

---
<img width="1260" height="767" alt="image" src="https://github.com/user-attachments/assets/abdcf2ed-494c-4eeb-a740-4d4654f7ad59" />

## Version 1 – Wine Dataset

Version 1 uses the **Wine dataset** from Scikit-learn.

In this version, I worked through the dataset, explored the data and created visualisations to understand it.

I then created a **Gradient Boosting Classifier** and used it as the starting model. The model was evaluated using the **weighted F1-score**.

The following feature-selection methods were covered:

* Variance Method
* K-Best Feature Selection
* Mutual Information
* Recursive Feature Elimination (RFE)
* Boruta

The results from the different methods were compared to see how selecting different features affected the model.

---

## Version 2 – Pima Indians Diabetes Dataset

Version 2 uses the **Pima Indians Diabetes dataset**.

The dataset was loaded and prepared by separating the input features from the target.

The following feature-selection methods were covered:

### Filter Method

The Filter Method used **SelectKBest** and the **Chi-squared test (`chi2`)** to select the best features.

### Wrapper Method

The Wrapper Method used **Recursive Feature Elimination (RFE)** together with **Logistic Regression**.

### Embedded Method

The Embedded Method introduced **Ridge Regression / L2 Regression**.

The provided notebook contains the heading for the Ridge Regression section, but no further code is included after that heading.

---

## Topics and Techniques Covered

The main topics covered in this project include:

* Loading datasets
* Exploring data
* Data preparation
* Data visualisation
* Train/test splitting
* Machine learning classification
* Gradient Boosting Classifier
* Logistic Regression
* F1-score
* Feature selection
* Variance Method
* K-Best
* Mutual Information
* Chi-squared
* Recursive Feature Elimination
* Boruta
* Ridge Regression / L2 Regression

---

## Repository Structure




Overall, this project gave me more practical experience with machine learning, feature selection and Python.
