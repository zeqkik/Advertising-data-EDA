# Advertising Data - Exploratory Data Analysis

## Project Description

This project aims to perform exploratory data analysis (EDA) on AdTech data obtained through a Single Store workspace. The dataset contains information related to advertising events, including advertiser details, viewer demographics, and campaign information. The goal is to derive meaningful insights and identify key patterns within the data.

A key aspect of this project was the treatment of missing data. For missing gender values, we applied an imputation technique based on the majority. Additionally, we implemented a custom imputation algorithm to handle missing income values, which considered multiple columns for a more accurate imputation. This algorithm was coded from scratch to ensure the imputation was contextually relevant, filling unknown entries with the majority value within the same gender, region, and country.

Additionally, the project focused on identifying the importance of various features using two statistical methods: the chi-squared (chi2) score test and the mutual information (MI) score. The chi2 score test helps determine if there is a significant relationship between categorical features and the target variable. The MI score provides a measure of the dependency between the feature and the target variable. 

**The tecnhices applied to deal with missing values and to calculate statistical importance of features were the main learnings in the project.**
