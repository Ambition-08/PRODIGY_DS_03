Bank Marketing Analysis

This project focuses on analyzing customer data from a bank marketing campaign to understand factors influencing customer responses to marketing calls. By leveraging machine learning techniques, particularly a Decision Tree Classifier, this project predicts the likelihood of a customer purchasing a product or service based on demographic and behavioral data. Key insights generated from this analysis can help banks refine their targeting strategies and optimize future marketing efforts. This repository includes code, datasets, and detailed documentation for each step of the analysis process.
Table of Contents

    Features
    Installation
    Data Collection
    Dataset Description
    Column Definitions
    Data Cleaning
    Data Analysis
    Sample Outputs
    License

Features

    Exploratory Data Analysis (EDA): Summary statistics and data visualization of customer demographics and behavior.
    Feature Engineering: Identification of important features influencing customer decisions.
    Classification Model: Decision Tree model to predict customer response.
    Evaluation Metrics: Accuracy, precision, recall, and F1-score for model performance.

Getting Started

Installation

Follow the instructions in the setup guide to install dependencies and run the analysis. Use the examples provided to replicate or customize the analysis for your own data.

To run this repository, install the following dependencies:

    Python: 3.11.8
    scikit-learn: 1.5.2
    pandas: 2.2.2
    NumPy: 1.26.4
    matplotlib: 3.8.0
    seaborn: 0.12.0

Additional Libraries: Essential libraries for this project are listed in libraries.ipynb.
File Illustration

Data Collection

Data is sourced from a bank marketing dataset provided in the repository. Alternatively, a similar dataset can be accessed on platforms like UCI's Bank Marketing Data Set.

Dataset Description

Dataset Description

This project uses a bank marketing dataset that contains demographic and financial details of customers who were targeted in a direct marketing campaign. Each entry represents a customer with a record of their engagement and response to the campaign.
Sample of the Dataset:
age	job	marital	education	default	balance	housing	loan	contact	day	month	duration	campaign	pdays	previous	poutcome	deposit
58	management	married	tertiary	no	2143	yes	no	unknown	5	may	261	1	-1	0	unknown	no
44	technician	single	secondary	no	29	yes	no	unknown	5	may	151	1	-1	0	unknown	no
33	entrepreneur	married	secondary	no	2	yes	yes	unknown	5	may	76	1	-1	0	unknown	no
47	blue-collar	married	unknown	no	1506	yes	no	unknown	5	may	92	1	-1	0	unknown	no
33	unknown	single	unknown	no	1	no	no	unknown	5	may	198	1	-1	0	unknown	no
Column Definitions:

    age: Age of the customer.
    job: Job type (e.g., management, technician, blue-collar, entrepreneur, etc.).
    marital: Marital status of the customer (e.g., single, married).
    education: Education level (e.g., secondary, tertiary).
    default: Whether the customer has a credit in default (yes/no).
    balance: Balance in the customer’s account.
    housing: Whether the customer has a housing loan (yes/no).
    loan: Whether the customer has a personal loan (yes/no).
    contact: Contact communication type (e.g., cellular, unknown).
    day: Day of the month when the customer was last contacted.
    month: Month when the customer was last contacted.
    duration: Duration of the last contact with the customer, in seconds.
    campaign: Number of contacts performed during this campaign for this customer.
    pdays: Number of days that passed after the customer was last contacted from a previous campaign; -1 means the customer was not previously contacted.
    previous: Number of contacts performed before this campaign.
    poutcome: Outcome of the previous marketing campaign (e.g., success, failure, unknown).
    deposit: Target variable, indicating whether the customer subscribed to the product (yes/no).

This dataset allows for a comprehensive analysis of customer demographics, financial status, and response to marketing strategies, making it a valuable resource for understanding factors influencing customer engagement in bank marketing campaigns.

Data Cleaning

The loading_data_and_data_cleaning.ipynb file includes code to prepare the dataset for analysis.
Data Analysis

    EDA on Bank Data: Analysis and visualization of key demographic and behavioral data (EDA_Bank_Marketing.ipynb).
    Model Building and Evaluation: Training a Decision Tree classifier to predict customer responses and evaluating its performance (Classification_Model.ipynb).

Sample Outputs

This repository contains sample outputs and visualizations generated from the analysis, located in the Sample_Outputs folder.
How to Contribute

If you'd like to contribute to this project or improve the analysis, please open a pull request or submit issues.
