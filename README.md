# World Happiness Report Analysis
## Description:

This project analyzes the World Happiness Report dataset, focusing on detecting and handling outliers in various socio-economic factors. The dataset includes columns like Happiness Score, GDP per Capita, Social Support, Life Expectancy, and more. The analysis involves identifying and visualizing outliers for these features to understand the distribution and quality of the data.


## Key Steps:

### Data Preprocessing:

The data is read from CSV files (e.g., property.csv), filtered for the city of Islamabad, and missing values are handled using imputation strategies.

The date_added column is converted to the datetime format.

### Outlier Detection:

Outliers are detected using the Interquartile Range (IQR) method for multiple columns, including:

Happiness Score

Happiness Rank

Economy (GDP per Capita)

Social Support

Life Expectancy

Freedom to make life choices

Generosity

Perceptions of Corruption

### Outlier Analysis:

For each feature, the program calculates the IQR, defines lower and upper bounds, and identifies values that fall outside these bounds as outliers.

The outliers are displayed for each feature, helping to highlight extreme values.

### Visualization:

The program visualizes outliers and their distribution using plots to aid in understanding the impact of extreme values on the dataset.

## Features:

Outlier Detection: Uses IQR method for identifying outliers across multiple columns.

Data Cleaning: Missing values are filled using mode imputation.
