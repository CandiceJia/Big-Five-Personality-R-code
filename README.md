# Big-Five-Personality-R-code
This code is useful for those who are willing to classify participants as "OCEAN" by using NEO-FFI data
# Reward Mechanism R code
Author: Candice
Date: 2023-07-24

Project Description
This project focuses on the analysis of reward mechanism data, especially exploring the relationship between individual personality traits and reward earnings. Data is sourced from multiple .csv files containing fields such as date, user identifier, reward schemes, and daily reward amounts.

Data Processing Workflow
Load Necessary R Packages: Incorporates multiple R packages like dplyr, ggplot2, car, among others.

Data Import:

Load all .csv files from the specified directory.
Combine these files to form a unified dataset.
Data Cleaning:

Remove unnecessary columns.
Convert date formats.
Remove all records prior to a specific date.
Exclude invalid user data.
Identify Reward Mechanism: Define a function to ascertain which type of reward mechanism is used for a given data record.

Merge with Personality Data: Combine the main dataset with the "Big Five Personality" dataset to explore the relationship between personality and rewards.

Data Transformation: Carry out transformations based on the Big Five personality traits.

Modeling and Statistical Analysis: Apply linear regression to analyze the interaction between personality traits and reward mechanisms.

Data Visualization: Use ggplot2 to create various data visualizations, including box plots, violin plots, and bar charts.

File Structure
Main data file path: C:/Users/晨希/Desktop/Psychological Science/dissertation/Reward Mechanism Data
Big Five Personality data: C:/Users/晨希/Desktop/Psychological Science/dissertation/Big Five Personality Data/merged_data.csv
Output files:
Reward_Condition.png
glance_results.csv
model_interactions.csv
model_interactions_weekdays.csv
... and more

How to Run
Ensure R and all necessary packages are installed.
Place the data files in the specified paths.
Execute the provided code in R or RStudio.

Conclusions
This section will detail the findings based on the models and visualizations.
