# The Demo file contains the steps to perform every Exploratory Analysis

 This will contain the template for every EDA project.

## Walkthrough
1. First, you need to have all command libraries for exploration and visualization.
2. Second, step is crucial because it helps to define 
the hypothesis(if not given) and the combination from where you can have the information.
3. Now Collect the data and store it in the panda's data frame for easy access.
4. Do the following mentioned analysis and form the relationship between various data features.
5. Test your hypothesis from the analysis and visualization.

# Contents

- Problem Definition/ Introduction
- Hypothesis Generation
- Data Extraction/ Data Collection
- Data Exploration and Transformation
- Hypothesis Testing

## Problem Definition/Introduction

Read the given data/information twice and try to understand it practically and theoretically and relate it to real life.
<br> Try to get what you can do with this data/information.
<br> Form some basic questions and hypotheses to work on that can be achieved with the available data/information.

## Hypothesis Generation

The hypothesis part should be done before any operation on the data.<br>
We can have both positive and negative hypotheses as well.
After deciding the hypothesis, Start operating and try to achieve hypothesis results, If your hypothesis is correct or incorrect mention it with reason in the conclusion.

## Data Extraction/ Data Collection

Collect the data from various sources and make it easy to handle or operate

Use the python libraries for data handling `pandas`, `numpy`,

## Data exploration and Transformation

This step contains the following actions

- Data Exploration
  - Check for data shape.
  - Check information(.info()) for checking the available data types.
    - Three types:
      - Numerical - Age, Contact Number (complete digit value)
      - Categorical - Class A, Class B, yes, no (multiple entries labeled with the same name)
      - Mixed - password, id (alpha-numeric values)
  - Check missing values or any other abnormal form of entries in the dataset.
  - Handle the missing and null entries.
- Univariate Analysis
  - It only focuses on analyzing each attribute independently(separately).
    - Perform Descriptive Analysis, and various statistical techniques including central tendency, frequency distribution,  dispersion, skewness and outliers also range, variance, standard deviation, and interquartile range(IQR). can be done with visualization.
- Univariate Analysis mainly focuses on mean, median, mode, range, IQR, skewness, and outliers.
  - For visualization plots like bar plot, density plot, hist plot, and KDE/hist plot.
- Bivariate Analysis<br>
    In bivariate analysis, analyze two features together.
  - Try to understand the relationship between two variables.
  - Bivariate Analysis can be done in 3 types based on the dataset(numerical, categorical)
    - Numerical - Numerical
      - Find a correlation coefficient between them
      - For visualization plots like scatterplot(regression plot),2D histplot, 2D KDEplot
    - Numerical - Categorical
      - Compare the distribution of categorical data corresponding to different categorical data.
      - Visualize it using barplot, boxplot, violin plot, and lmplot.
    - Categorical - Categorical
      - Form the cross-tabulation or contingency tables to show the distribution of category values over other category values.
      - In other words - You can create cross-tabulations or contingency tables that show the distribution of values in one categorical column, grouped by the values in the other categorical column.
      - For visualization plots like. heatmap, stacked bar plots, treemaps.

## Hypothesis Testing

From the above analysis and graphs test the hypothesis you have made in the Second Step.
Perform the hypothesis which is generated in Second Step, then go through the data exploration/visualization and verify the hypothesis.
Mention the results which are obtained from the entire testing process.