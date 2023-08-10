# Snowflake for data science

## 1. Introduction

Snowflake is often thought of as only a database/storage service. However, in this session I will show how the Snowflake ecosystem can be used as and end-to-end solution for a data science application.

## 2. Overview

This example is based on the Machine Learning for Credit Card Fraud detection - Practical handbook, https://fraud-detection-handbook.github.io/fraud-detection-handbook/

It shows how to do Feature Engineering with Snowpark, preparing data for training a Machine Learning model and finaly how to deploy and use a trained model in Snowflake using Python UDF.

## 3. Prerequisite

* Snowflake account (I'm using a trial account)
* Snowpark for Python version 0.12.0 or later
* Jupyter or JupyterLab
* Enable third party Anaconda packages
* The examples also use the following Python libraries:
  ```
  scikit-learn
  pandas
  joblib
  cachetools
  numpy
  matplotlib
  ```

## 4. What you'll learn

* Using Snowpark to interact programmatically with Snowflake
* How to use Snowpark for Python for doing Feature Engineering
* Training a Machine Learning model outside of Snowflake and to deploy it as a Python UDF
