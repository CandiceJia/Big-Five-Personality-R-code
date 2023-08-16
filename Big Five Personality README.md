# Big Five Personality Data Analysis

**Author**: Candice  
**Date**: 2023-06-05

## Overview

This project focuses on processing and analyzing the "Big Five Personality Test" data. The goal is to reformat, score, and merge the data with demographic information, then rank individual scores based on gender-specific criteria. This code is useful for those who are willing to classify participants as "OCEAN" by using NEO-FFI data.

## Process Flow

1. **Load Required Packages**: Utilize `readxl` and `dplyr` packages for data reading and manipulation.

2. **Data Reading**:
    - Import data from the "THE BIG FIVE PERSONALITY TEST(1-44).xlsx" file.
    - Rename columns for better clarity and consistency.

3. **Data Transformation**:
    - Adjust questionnaire scores.
    - Apply reverse scoring on specific items.
    - Convert character data types to numeric where necessary.
    - Calculate aggregate scores for each of the Big Five dimensions: Neuroticism, Extraversion, Openness, Agreeableness, and Conscientiousness.

4. **Data Refinement**:
    - Extract key columns to create a new dataset with unique codes and personality scores.
    - Import additional demographic data from "Demographic Form(1-42).xlsx".
    - Merge the two datasets based on unique codes.

5. **Scoring & Classification**:
    - Rank individual scores in various personality dimensions based on predefined thresholds, separated by gender.

6. **Data Export**: Save the merged and processed data to a `.csv` file.

## File Structure

- Main personality data: "THE BIG FIVE PERSONALITY TEST(1-44).xlsx"
- Demographic data: "Demographic Form(1-42).xlsx"
- Output file: "Big Five Personality Data/merged_data.csv"

## Getting Started

1. Make sure you have R installed along with the `readxl` and `dplyr` libraries.
2. Place the source data files in the appropriate directory.
3. Execute the R code provided in either R or RStudio.

## Notes

- The analysis assumes specific scoring guidelines based on the Big Five questionnaire's structure.
- The ranking criteria vary between males and females and are determined by predefined thresholds for each dimension.
