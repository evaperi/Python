This repository contains machine learning projects developed during my Master’s studies in Business Administration, Analytics, and Information Systems.

The repository includes:

Coursework assignments implementing core machine learning algorithms

My Master’s thesis project on predicting hotel booking cancellations

All analyses are implemented using Python and Jupyter Notebooks and follow a reproducible data science workflow including data exploration, preprocessing, modeling, and evaluation.

**Master’s Thesis Project**
Predicting Hotel Booking Cancellations Using Machine Learning
Overview

This project analyzes hotel booking demand with the goal of predicting whether a hotel reservation will be canceled or not.

The analysis uses a real-world dataset containing 119,390 hotel booking records, including information about booking details, customer characteristics, and stay conditions.

Predicting cancellations is valuable for hotels because it helps improve revenue management, occupancy planning, and pricing strategies.

**Project Workflow**

The analysis follows a standard machine learning pipeline.

**1. Exploratory Data Analysis (EDA)**

Initial exploration of the dataset to understand its structure and patterns.

Tasks included:

Distribution analysis of booking characteristics
Visualization of cancellation patterns
Identification of potential correlations between features
Examination of missing values and anomalies

**2. Data Cleaning and Preparation**

The dataset required several preprocessing steps before modeling.

Tasks included:

Cleaning inconsistent records
Handling missing values
Encoding categorical features
Feature transformation where necessary
Correlation analysis and statistical testing to understand relationships between variables

The final dataset contained 86,192 observations ready for modeling.

**3. Machine Learning Models**

Several classification algorithms were implemented and compared to predict booking cancellations:

Decision Tree
Random Forest
XGBoost

Hyperparameter tuning was performed using:
GridSearch Cross Validation

The models were trained on a training dataset and evaluated on a test dataset to measure predictive performance.

**4. Model Evaluation**

Model performance was evaluated using multiple metrics:

Accuracy
Precision
Recall
F1-score
PR-AUC

Special emphasis was placed on Recall, aiming to detect as many booking cancellations as possible while maintaining balanced performance across the other metrics.

**Coursework Project – Machine Learning Algorithms**

This project involves the application of Machine Learning algorithms on at least two different datasets. 
The algorithms are divided into three categories: Regression Clustering Classification 

For each algorithm category, a separate .ipynb notebook file has been created, while all datasets are stored in the folder. Each notebook contains all necessary steps for applying the algorithm and evaluating its performance. 
How to Use Prerequisites: Ensure you have the required Python libraries installed: pip install pandas numpy matplotlib seaborn scikit-learn 

Notebook Content 
Each notebook follows a similar structure: 
Importing Libraries: Loading all necessary Python libraries. 
Loading & Inspecting Data: Overview of feature types, target variable, and basic dataset information. 
Exploratory Data Analysis (EDA): Visualizations and descriptive statistics to understand the data. 
Data Preparation: Handling missing values, encoding categorical variables, splitting into training and test sets, and scaling features if needed. 
Algorithm Implementation: Application of the algorithm with multiple variations or parameter settings. For classification, predictions for a new hypothetical observation are also included. 
Performance Evaluation: Measuring accuracy/performance of each algorithm and comparing the results. The most effective algorithm is highlighted with comments on why it performs best.
