# Exploratory Data Analysis (EDA) on Medical Insurance Dataset

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a medical insurance dataset to understand the factors that influence individual insurance charges. The analyses explores relationships between demographic, lifestyles, and medical attributes to uncover patterns that impact healthcare costs.

## Objectives
- Understand the structure and composition of the dataset.
- Identify and handle missing values (if any).
- Perform descriptive statistical analysis.
- Explore relationships between features and insurance charges.
- Detect patterns, trends, and potential outliers.
- Prepare insights for future predictive modelling.

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Dataset Description
The dataset contains information about individuals and their medical insurance costs.

### Features include:
- age: Age of the individual
- sex: Gender (male/female)
- bmi: Body Mass Index
- children: Number of children covered
- smoker: Smoking status (yes/no)
- region: Residential area in the US
- charges: Medical insurance cost (target variable)

## Data Cleaning & Preprocessing
- Checked for missing values (none found in the dataset)
- Verified data types and consistency
- Converted categorical variables (sex, smoker, region) into numerical format using encoding techniques
- Ensured dataset was ready for analysis and visualization

## Exploratory Data Analysis

### 1.Distribution Analysis
- Distribution of age and insurancecharges was visualized
- Charges showed a right-skewed distribution, indicating most individuals have lower insurance costs with afew high-cost ouliers

### 2.Relationship Between Variables
- Age vs Charges: Older individuals tend to have higher insurance costs.
- BMI vs Charges: Higher BMI is associated with increased medical costs.
- Smoker vs Charges: Smokers have significantly higher insurance charges compared to non-smokers.
- Children vs Charges: Slight variation in charges depending on number of children

## Categorical Analysis
- Smokers contribute disproportionately to higher insurance costs
- Regional differences in charges are present but less significant compared to smoking status

  ## Correlation Analysis
  - Strong positive correlation between smoking status and charges
  - Moderate correlation between BMI and charges
  - Weak correlation between age and BMI
 
  ## Key Insights
  - Smoking is the strongest factor influencing insurance charges
  - Individuals with higher BMI generally incur higher medical costs
  - Age has a gradual positive relationship with insurance charges
  - Most customers fall into low-to-moderate charge ranges, with a few high-cost outliers
 
  ## Conclusion
  This EDA provided valuable insights into the medical insurance dataset, highlighting key factors that influence insurance charges. The findings suggest that lifestyle factors, particularly smoking and BMI, play a major role in determining healthcare costs. These insights can be used as a foundation for building predictive models such as linear regression.
