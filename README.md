Bank Marketing Campaign Analysis

This project provides an analysis of a bank's direct marketing campaign data, aiming to predict whether a customer will subscribe to a term deposit based on demographic and behavioral factors. By leveraging data science techniques, this project explores insights into customer responses, offering actionable information for future marketing strategies.
# Table of Contents
- [Introduction](#introduction)
- [Getting_Started](#Getting_Started)
- [Repository_File_Structure](#Repository_File_Structure)
- [Data Collection and Description](#data_collection_and_description)
- [Data_Sample](#Data_Sample)
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

   # Bank Marketing Campaign Analysis

This repository contains files and resources for the Bank Marketing Campaign Analysis project, which uses demographic and behavioral data to predict whether a customer will subscribe to a term deposit.

## Repository Contents

- [Bank_marketing_Campaign.ipynb](Bank_marketing_Campaign.ipynb): Jupyter notebook with the complete data analysis, including data cleaning, exploration, and predictive modeling.
- [bank-full.csv](bank-full.csv): The dataset used in this analysis, containing information on customer demographics, financial status, and interactions with the bank.
- [.gitignore](.gitignore): Specifies files and directories that should be ignored by Git.
- [LICENSE](LICENSE): License details for the project.
- [README.md](README.md): This README file, which provides an overview of the project, dataset, and file descriptions.

## Data_Collection_and_Description

The dataset bank-full.csv includes 17 attributes on customer demographics, financial history, and response to the bank campaign. The key columns include:
### Data_Sample

Below is a sample of the `bank-full.csv` dataset, showcasing the attributes used for analysis.

| age | job          | marital | education | default | balance | housing | loan | contact | day | month | duration | campaign | pdays | previous | poutcome | deposit |
|-----|--------------|---------|-----------|---------|---------|---------|------|---------|-----|-------|----------|----------|-------|----------|----------|---------|
| 58  | management   | married | tertiary  | no      | 2143    | yes     | no   | unknown | 5   | may   | 261      | 1        | -1    | 0        | unknown  | no      |
| 44  | technician   | single  | secondary | no      | 29      | yes     | no   | unknown | 5   | may   | 151      | 1        | -1    | 0        | unknown  | no      |
| 33  | entrepreneur | married | secondary | no      | 2       | yes     | yes  | unknown | 5   | may   | 76       | 1        | -1    | 0        | unknown  | no      |
| 47  | blue-collar  | married | unknown   | no      | 1506    | yes     | no   | unknown | 5   | may   | 92       | 1        | -1    | 0        | unknown  | no      |
| 33  | unknown      | single  | unknown   | no      | 1       | no      | no   | unknown | 5   | may   | 198      | 1        | -1    | 0        | unknown  | no      |

**Column Definitions**:

- **age**: Customer’s age
- **job**: Occupation type
- **marital**: Marital status
- **education**: Education level
- **default**: Has credit in default? (yes/no)
- **balance**: Average yearly balance in euros
- **housing**: Has a housing loan? (yes/no)
- **loan**: Has a personal loan? (yes/no)
- **contact**: Contact communication type
- **day** and **month**: Last contact day and month
- **duration**: Last contact duration in seconds
- **campaign**: Number of contacts during this campaign
- **pdays**: Days since last contact with the customer
- **previous**: Number of previous contacts
- **poutcome**: Outcome of the previous marketing campaign
- **deposit**: Target variable indicating if the customer subscribed (yes/no)

This sample illustrates the diversity in customer demographics and attributes that influence their response to the bank's marketing campaigns.

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
