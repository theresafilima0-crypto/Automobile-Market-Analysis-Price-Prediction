## Automobile Market Analysis & Price Prediction
## Overview

Analyzed 5,500 automobile records using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. Cleaned and explored vehicle data, investigated relationships between vehicle specifications and selling prices, visualized key patterns, and applied regression analysis for price prediction.

# Project Objectives

The main objectives of this project were to:

Explore and understand the structure of automobile data.
Identify missing values and data-quality issues.
Perform exploratory data analysis (EDA).
Examine relationships between vehicle characteristics and selling price.
Compare automobile brands and vehicle characteristics.
Create visualizations to communicate patterns in the data.
Apply linear regression to explore price relationships.
Develop practical data-analysis and machine-learning skills using Python.

## Dataset

The dataset contains 5,500 rows and 18 columns.

# Key Variables
Variable	Description
Make	Vehicle manufacturer/brand
Model	Vehicle model
Year	Vehicle manufacturing year
Fuel_Type	Type of fuel used
Transmission	Vehicle transmission type
Engine_Size	Engine size
Mileage	Vehicle mileage
Horsepower	Vehicle horsepower
Torque	Vehicle torque
Owners	Number of previous owners
Accident_History	Accident history indicator
Service_History	Vehicle service history
Color	Vehicle color
Body_Type	Vehicle body type
Drivetrain	Vehicle drivetrain
Fuel_Efficiency	Fuel efficiency
Location	Vehicle location
Selling_Price	Vehicle selling price

The dataset was loaded from automobile_dataset.csv and contains both numerical and categorical variables, with missing values present in several fields.

## Data Source

Automobile Dataset — provided for educational and analytical purposes.

## Tools & Technologies
Python
Pandas — data manipulation and analysis
NumPy — numerical operations
Matplotlib — data visualization
Seaborn — statistical visualization
Scikit-learn — machine learning and linear regression
Jupyter Notebook — analysis environment

## Analysis Process

The project follows a structured data-analysis workflow:

1. Data Loading

The automobile dataset was imported into Python using Pandas.

import pandas as pd

df = pd.read_csv("automobile_dataset.csv")
2. Data Exploration

The dataset was explored to understand:

Number of records and variables
Data types
Column structure
Sample records
Missing values
Numerical and categorical variables

The dataset contains 5,500 records and 18 columns.

3. Data Cleaning

The analysis examined missing values across the dataset and individual automobile-brand subsets.

This step was important because several variables contain missing observations, including engine size, transmission, horsepower, torque, service history, color, fuel efficiency, and location.

4. Exploratory Data Analysis

Exploratory analysis was performed to investigate relationships between:

Vehicle age and selling price
Mileage and selling price
Engine size and selling price
Horsepower and selling price
Vehicle brands and selling price
Other vehicle characteristics and pricing
5. Data Visualization

Matplotlib and Seaborn were used to create visualizations that make patterns and relationships easier to interpret.

The visual analysis helps examine distributions, comparisons, and relationships between automobile characteristics.

6. Brand-Level Analysis

The dataset was also examined by individual automobile manufacturers, including brands such as:

Toyota
BMW
Mercedes-Benz
Chevrolet
Ford

This allowed the analysis to explore whether relationships between vehicle characteristics and selling price differed across brands.

7. Regression Analysis

Linear regression was introduced to explore the relationship between vehicle characteristics and selling price.

The notebook includes regression models using vehicle year as a predictor of selling price, as well as exploratory brand-specific regression analysis.

## Key Questions

The analysis was designed around questions such as:

How does vehicle year relate to selling price?
How does mileage relate to vehicle price?
What relationship exists between engine size and selling price?
How are horsepower and torque related to vehicle prices?
How does pricing vary across automobile brands?
What patterns can be identified through exploratory visualization?
Can vehicle characteristics provide useful information for predicting selling price?

## Key Takeaways

This project demonstrates how Python can be used to move from a raw dataset to structured analysis.

The analysis provided practical experience in:

Inspecting real-world-style datasets.
Identifying missing data.
Working with numerical and categorical variables.
Filtering and analyzing subsets of data.
Creating visualizations.
Investigating relationships between variables.
Applying basic regression techniques.
Communicating analytical findings.

Note: The regression component is exploratory and should not be interpreted as a production-ready vehicle pricing model. Further feature engineering, categorical encoding, train/test splitting, model evaluation, and validation would be required for a robust predictive system.

## Project Structure
Automobile_Market_Analysis
│
├── Automobile_Market_Analysis.ipynb
├── automobile_dataset.csv
└── README.md

## Future Improvements

To further develop this project, I would:

Perform more systematic missing-value treatment.
Detect and handle potential outliers.
Encode categorical variables for machine learning.
Use multiple vehicle characteristics as model features.
Split the dataset into training and testing sets.
Compare multiple regression algorithms.
Evaluate models using metrics such as MAE, MSE, RMSE, and R².
Perform feature engineering and feature selection.
Build an interactive dashboard using Power BI or Tableau.
Develop a more robust automobile price prediction model.

## Skills Demonstrated

Data Analysis | Data Cleaning | Exploratory Data Analysis | Data Visualization | Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Machine Learning | Linear Regression

## Author

Theresa Filima

Aspiring Data Analyst | AI Automation | Machine Learning | Data Science

This project was developed as part of my practical learning journey in Data Analytics, Machine Learning, and Python.


## Project Files

[View the Jupyter Notebook](Automobile_Market_Analysis_Price_Prediction.ipynb)


