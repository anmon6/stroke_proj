# Stroke Risk Estimator: Project Overview

- Analyzed a dataset to determine significant predictors of stroke risk.
- Imported stroke-related data from an Excel file using the Pandas library.
- Utilized multiple regression analysis to identify the statistical significance of each variable in predicting stroke risk.
- Generated various visualizations using the matplotlib library to illustrate the findings.

## Code Used
**Python Version** 3.9

**Packages:** pandas, sklearn, matplotlib

## Model Building
First, I transformed the categorical variables into dummy variables. Then, I utilized multiple linear regression and calculated the correlation coefficient to assess the model's ability to predict the risk of stroke based on age, blood pressure, and smoking status.

Additionally, I created a new data frame that includes the actual risk and predicted risk to analyze the model's results and check for bias. The results are visualized in the plot below:
