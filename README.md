# Boston Housing Data Analysis

This project analyzes the Boston Housing dataset to extract insights about housing prices and various factors influencing them.

## Project Goal

The main objective of this project is to leverage statistical analysis and visualization techniques to answer key questions about the Boston housing market, providing valuable insights to stakeholders such as a housing agency in Boston, MA.

## Dataset

The dataset used in this analysis is the Boston Housing dataset, derived from the U.S. Census Service. It contains information on various features of housing units in Boston, including crime rate, proximity to the Charles River, and median home value. 

[More information on the data can be found in the Jupyter Notebook](boston_housing.ipynb)

## Key Questions

The project seeks to answer the following questions:
1. Is there a significant difference in the median value of houses bounded by the Charles river or not?
2. Is there a difference in median values of houses of each proportion of owner-occupied units built before 1940?
3. Can we conclude that there is no relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town?
4. What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?


## Statistical Methods
The project utilizes the following statistical methods for data analysis:
* **T-test for independent samples**: To compare the median values of houses based on their proximity to the Charles River.
* **ANOVA**: To analyze the median values of houses across different age groups.
* **Pearson Correlation**: To determine the relationship between nitric oxide concentration and the proportion of non-retail business acres.
* **Regression Analysis**: To assess the impact of distance to employment centers on the median value of owner-occupied homes.

## Project Structure
* **boston_housing.ipynb**: This Jupyter Notebook contains the project code, including data loading, data cleaning, exploratory data analysis, statistical tests, and visualizations.

## Requirements
* Python
* Libraries: NumPy, Pandas, Matplotlib, Seaborn, Statsmodels, Scipy.

## Running the Notebook
Clone this repository, install the required libraries, and then open the `boston_housing.ipynb` notebook. You can run the code cells in the notebook to reproduce the analysis.

## Results and Conclusions

Key findings from the data analysis include:
* There is a statistically significant difference in the median values of houses bounded by the Charles River.
* There is a significant difference in the median house prices for different age groups.
* There is a positive relationship between nitric oxide concentration and the proportion of non-retail business acres.
* The weighted distance to five Boston employment centers has a negative impact on the median value of owner-occupied homes.


## Author
Aravindan Natarajan

## Date
24-Aug-2024
