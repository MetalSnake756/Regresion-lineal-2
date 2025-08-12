# Linear Regression

This notebook's main objective is to develop a real estate valuation system using a linear regression model, which is a common machine learning technique. 🏡💰

## Overview
The project aims to develop a real estate valuation system using linear regression, a fundamental machine learning methodology. The dataset consists of 5,000 randomly sampled properties available for sale in the municipality of Rio de Janeiro.

## Dataset Description
The dataset includes the following variables:

* Value: Offer price of the property in US dollars.

* Area: Area of the property in square meters.

* Dist_Playa: Distance from the property to the beach in kilometers (straight line).

* Dist_Farmacia: Distance from the property to the nearest pharmacy in kilometers (straight line).

### Dataset Characteristics
* Size: 5,000 entries.

* Columns: 4 (Value, Area, Dist_Playa, Dist_Farmacia).

* Data Types:
    * Valor: Integer (int64).

    * Area: Integer (int64).

    * Dist_Playa: Float (float64).

    * Dist_Farmacia: Float (float64).

## Key Analyses
1. Descriptive Statistics: Basic statistical measures (mean, standard deviation, min, max, quartiles) for each variable.

2. Correlation Matrix: Examines the linear relationships between variables.

    * Value shows a strong positive correlation with Area (0.7110) and a moderate negative correlation with Dist_Playa (-0.3665).

    * Dist_Farmacia has a negligible correlation with Value (-0.0244).

3. Visualizations:

    * Box Plot: Analyzes the distribution of property prices.

    * Distribution Plot: Displays the frequency distribution of property prices, highlighting skewness and outliers.

## Libraries Used
Pandas: For data manipulation and analysis.

Seaborn: For statistical visualizations.

Matplotlib: For creating plots and charts.

## Project Goals
Understand the Dataset: Explore the dataset to identify patterns and relationships.

Preliminary Analysis: Perform statistical and visual analyses to summarize the data.

Model Development: Use linear regression to predict property values based on features like area and distances to amenities.

## Usage
Data Loading: The dataset is loaded from a CSV file (dataset.csv).

Exploration: The notebook includes steps to view the data, check its structure, and compute descriptive statistics.

Visualization: Various plots are generated to understand the distribution and relationships between variables.

Correlation Analysis: The correlation matrix helps identify potential predictors for the regression model.

## Key Insights
The dataset contains properties with a wide range of values, from $13,863 to $4,621,072.

The average property area is approximately 122 m², with significant variability (standard deviation of 90.54 m²).

Properties closer to the beach tend to have higher values, as indicated by the negative correlation between Value and Dist_Playa.

## Next Steps
Feature Engineering: Create new variables or transform existing ones to improve model performance.

Model Training: Implement linear regression and evaluate its performance using metrics like R-squared and RMSE.

Validation: Split the data into training and testing sets to validate the model.
