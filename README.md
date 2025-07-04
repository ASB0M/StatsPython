### Boston Housing Price Analysis
This project explores the Boston Housing dataset to analyze various factors influencing median home values. The analysis is performed using Python within a Jupyter Notebook environment, leveraging libraries such as pandas, seaborn, matplotlib, scipy.stats, and statsmodels.

### Project Overview
The primary goal of this project is to conduct an exploratory data analysis (EDA) on the Boston Housing dataset. We investigate relationships between different housing attributes and the median value of owner-occupied homes (MEDV). This includes:

- Descriptive statistics of the dataset.

- Visualizing the distribution of median home values using a box plot.

- Comparing median home values for tracts bounded by the Charles River versus those not bounded.

- Analyzing the relationship between the age of owner-occupied units and their median value.

- Performing a T-test to compare median values of homes with different Charles River proximity.

- Conducting an ANOVA test to compare median values across different age groups of homes.

- Implementing a regression analysis to determine the impact of nitric oxides concentration on median home values.

### Dataset
The dataset used is the Boston Housing Dataset, which contains information about houses in various Boston suburbs. The dataset is loaded directly from a URL within the notebook.

Key variables in the dataset include:

CRIM: Per capita crime rate by town

ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: Proportion of non-retail business acres per town.

CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)

NOX: Nitric oxides concentration (parts per 10 million)

RM: Average number of rooms per dwelling

AGE: Proportion of owner-occupied units built prior to 1940

DIS: Weighted distances to five Boston employment centers

RAD: Index of accessibility to radial highways

TAX: Full-value property-tax rate per $10,000

PTRATIO: Pupil-teacher ratio by town

LSTAT: % lower status of the population

MEDV: Median value of owner-occupied homes in $1000's

### Analysis Performed
The notebook includes the following analytical steps:

- Data Loading and Inspection: Loading the boston_housing.csv dataset and displaying its head and descriptive statistics.

- Box Plot for Median Home Value (MEDV): Visualizing the distribution of MEDV to identify central tendency and outliers.

- Bar Plot for Charles River (CHAS) vs. MEDV: Comparing the median home values for properties located near the Charles River versus those that are not.

- Box Plot for MEDV vs. AGE Group: Categorizing AGE into groups (35 years and less, 35-75 years, 75 years and older) and visualizing the median home value for each group.

- T-test for CHAS and MEDV: Statistical test to determine if there is a significant difference in median home values between properties bounded by the Charles River and those not.

- ANOVA for AGE Groups and MEDV: Performing an ANOVA test to check for significant differences in median home values across the defined age groups.

- Regression Analysis (NOX vs. MEDV): Building a linear regression model to assess the impact of nitric oxides concentration on the median value of owner-occupied homes.

### Execute the cells:
Once the notebook is open, you can run each cell sequentially to see the data loading, analysis, and visualizations.

### Libraries Used
- pandas: For data manipulation and analysis.

- numpy: For numerical operations.

- seaborn: For statistical data visualization.

- matplotlib.pyplot: For plotting and visualization.

- scipy.stats: For statistical functions (e.g., T-tests, ANOVA).

- statsmodels: For statistical modeling, including regression analysis.

### Results Highlights
- Median Home Value Distribution: The median home values (MEDV) are mostly centered around $17,000 - $25,000, with some outliers extending up to $50,000.

- Charles River Proximity: Properties bounded by the Charles River tend to have higher median values compared to those not bounded by the river.

- Age of Homes: The analysis indicates differences in median home values based on the age of the owner-occupied units.

- Nitric Oxides Concentration: The regression analysis provides insights into how NOX levels are associated with MEDV.

Disclaimer: This project is for educational purposes as part of a peer-graded assignment from Skills Network. The dataset and analysis are based on the provided lab instructions.
