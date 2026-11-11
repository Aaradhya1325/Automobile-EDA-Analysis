**# Automobile EDA Analysis

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an automobile dataset using Python. The analysis examines automobile specifications, pricing, fuel types, body styles, drivetrain characteristics, and other technical variables to identify patterns and relationships within the dataset.

The project was completed as part of a four-week Automotive Data Analyst Internship.

## Objectives

- Understand the structure and quality of the automobile dataset.
- Identify and handle missing values.
- Perform data cleaning and preprocessing.
- Explore numerical and categorical variables.
- Analyze factors associated with automobile prices.
- Create meaningful visualizations to communicate findings.
- Identify important relationships and trends in the automotive dataset.

## Dataset

The dataset used for this project is the **UCI Automobile Dataset**, containing information about 205 automobiles and 26 variables, including automobile specifications and price.

Dataset source: UCI Machine Learning Repository

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Methodology

The analysis followed these major steps:

1. Dataset collection and initial inspection
2. Data quality assessment
3. Missing-value analysis
4. Data cleaning and preprocessing
5. Univariate analysis
6. Bivariate analysis
7. Correlation analysis
8. Visualization and interpretation
9. Identification of key automotive insights
10. Documentation of findings, challenges, and limitations

## Key Findings

- Engine size showed a strong positive relationship with automobile price, with a correlation of approximately **0.86**.
- Curb weight also had a strong positive relationship with price, with a correlation of approximately **0.82**.
- Horsepower showed a strong positive correlation with price of approximately **0.75**.
- Highway MPG and city MPG showed strong negative relationships with price.
- Rear-wheel-drive vehicles had a substantially higher average price than front-wheel-drive vehicles in this dataset.
- Turbocharged vehicles had a higher average price than vehicles with standard aspiration.
- Hardtop and convertible vehicles had higher average prices, although these categories contained relatively few observations.
- The dataset was dominated by gasoline vehicles and sedan/hatchback body styles.

## Data Cleaning

Missing numerical values were handled using median imputation, while the missing categorical value in `num-of-doors` was filled using the mode.

The dataset initially contained missing values in several variables, including `normalized-losses`, `stroke`, `bore`, `peak-rpm`, `horsepower`, `price`, and `num-of-doors`.

No duplicate rows were identified.

## Challenges and Limitations

- The dataset contained missing values across multiple variables.
- `normalized-losses` had approximately 20% missing values.
- Some categories had relatively small sample sizes, which can affect comparisons.
- Potential price outliers were identified but retained because they may represent genuine high-value vehicles.
- Median imputation was used to preserve the dataset size.
- Correlation analysis identifies relationships between variables but does not establish causation.

## Project Files

- `Week2_Automobile_EDA_Analysis.ipynb` – Complete Python analysis and visualizations.
- `automobile_cleaned_dataset.csv` – Cleaned dataset used for analysis.

## Conclusion

The exploratory analysis identified several important relationships between automobile specifications and pricing. Engine size, curb weight, horsepower, vehicle dimensions, and fuel economy were among the variables most strongly associated with price. The analysis demonstrates how data cleaning, statistical analysis, visualization, and interpretation can be applied to automotive datasets to support data-driven understanding of vehicle characteristics and pricing.

## Author

Aaradhya Minajgi
Automotive Data Analyst Intern**
