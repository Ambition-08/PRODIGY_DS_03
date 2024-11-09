Bank Marketing Campaign Analysis

This project provides an analysis of a bank's direct marketing campaign data, aiming to predict whether a customer will subscribe to a term deposit based on demographic and behavioral factors. By leveraging data science techniques, this project explores insights into customer responses, offering actionable information for future marketing strategies.
# Table of Contents
- [Introduction](#introduction)
- [Getting_Started](#Getting_Started)
- [Repository_File_Structure](#Repository_File_Structure)
- [Data Collection and Description](#data_collection_and_description)
- [Data_mining](#Data_mining)
- [Sample_Outputs](#sample_outputs)
- [License](#license)

## Introduction

This project analyzes a dataset from a bank’s direct marketing campaign, identifying patterns in customer demographics and financial attributes to understand factors influencing customer engagement. By building and tuning a Decision Tree classifier, this project aims to predict customer subscription to the term deposit product.
Features

    Exploratory Data Analysis (EDA) for uncovering data insights
    Predictive Model using Decision Tree classifier
    Feature Importance Analysis to understand the drivers of customer behavior
    Hyperparameter Tuning for model optimization

## Getting_Started

Clone the repository and follow the installation instructions to set up the project environment. The repository includes Jupyter notebooks with code, data, and sample outputs for easy reproduction of the analysis.
Installation

To set up the environment, ensure you have Python 3.11.8 installed, along with the following libraries:

    TensorFlow: 2.18.0
    Keras: 3.6.0
    Pandas: 2.2.2
    NumPy: 1.26.4
    h5py: 3.12.1
    scikit-learn: 1.5.2

Additional dependencies can be installed by running:

pip install -r requirements.txt

### Repository_File_Structure

    .gitignore: Excludes unnecessary files from version control.
    Bank_marketing_Campaign.ipynb: Main Jupyter notebook with code for data cleaning, EDA, and modeling.
    LICENSE: License file for project usage terms.
    README.md: Overview and instructions for project usage.
    bank-full.csv: Dataset containing customer demographic and behavioral data, used for analysis and modeling.

## Data_Collection_and_Description

The dataset bank-full.csv includes 17 attributes on customer demographics, financial history, and response to the bank campaign. The key columns include:

    age: Customer age
    job: Occupation type
    marital: Marital status
    education: Education level
    default: Credit in default (yes/no)
    balance: Average yearly balance in euros
    housing: Housing loan status
    loan: Personal loan status
    contact: Contact communication type
    day and month: Last contact day and month
    duration: Last contact duration in seconds
    campaign: Number of contacts performed during the campaign
    pdays: Days since the customer was last contacted
    previous: Number of contacts before this campaign
    poutcome: Outcome of the previous campaign
    deposit: Target variable indicating subscription (yes/no)

## Data_mining

Initial data preprocessing involves handling missing values, encoding categorical variables. This ensures data quality and consistency before analysis.
Data Analysis

    Exploratory Data Analysis: Understanding distribution, correlations, and patterns within the data.
    Model Training: Training a Decision Tree classifier to predict the likelihood of term deposit subscription.
    Feature Importance: Identifying the most influential features on customer decisions.
    Hyperparameter Tuning: Adjusting model parameters to enhance prediction accuracy.

## Sample_Outputs

The repository includes sample outputs, such as:

    Feature Importance Plot: Visualization of key features influencing the model’s predictions.
    Model Performance Metrics: Accuracy and validation scores of the classifier.

## License

This project is licensed under the MIT License, permitting free use, modification, and distribution.
