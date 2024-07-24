# Vaccine Project Analysis

This repository contains the analysis and findings from the Vaccine Project, which explores the relationship between vaccination rates and health outcomes using various statistical and machine learning techniques.

## Explanation of Analysis and Findings

### Descriptive Statistics

**Descriptive Statistics Table**

- **Count, Mean, Standard Deviation, Minimum, Maximum**: This table provides a summary of the dataset's key statistical features. It helps in understanding the general behavior of the data, such as central tendencies (mean) and dispersion (standard deviation).

### Visualizations

**Histograms**

- **Purpose**: To provide insights into the distribution of vaccination rates across the dataset. This visualization helps in understanding the frequency and spread of various vaccination statuses.

**Box Plots**

- **Purpose**: To show the distribution of rates with respect to different categories and to spot outliers. This helps in identifying unusual values that could affect the analysis and model performance.

**Correlation Matrix (Heatmap)**

- **Purpose**: To visualize the relationships between different types of rates (unvaccinated, vaccinated, boosted) and health outcomes. This is crucial for identifying potential predictors for the outcome variables and understanding the interdependencies among various factors in the dataset.

### Regression Analysis

**OLS Regression Results**

- **R-squared (R²)**: Represents the percentage of the response variable variation explained by the linear model. An R² value close to 1 suggests that the model explains a great deal of the variance.
- **Coefficients**: Indicate the nature and strength of the relationship between each predictor and the outcome variable. Positive coefficients suggest a direct relationship, whereas negative coefficients suggest an inverse relationship.
- **P-values**: Provide information on the statistical significance of each coefficient. A low p-value (typically < 0.05) indicates strong evidence against the null hypothesis, confirming the predictor's influence on the outcome variable.

### Predictive Modeling

**Random Forest Classifier Accuracy**

- **Purpose**: Measures the proportion of true results (both true positives and true negatives) among the total number of cases examined. High accuracy in this context suggests that the model effectively distinguishes between the classes based on the given predictors.

## Repository Contents

- **Vaccine Project .ipynb**: Jupyter Notebook containing the full analysis, visualizations, and model results.
- **data/**: Directory containing the dataset used for the analysis.
- **results/**: Directory containing the output files such as figures and tables generated during the analysis.
- **README.md**: This file, providing an overview of the project and its contents.
