# Student Performance Analysis: Predicting Academic Achievements

In this project, we investigate the myriad of factors that influence academic performance among students. The dataset at hand offers a comprehensive view of 10,000 student records, delving into a range of predictors that collectively shape a student's academic trajectory. The overarching goal is to understand and predict the performance index, a metric encapsulating the academic achievements of the students.

## Overview:

The primary objective is to use statistical methods and machine learning techniques to predict the performance index based on various predictors. This prediction can aid educational institutions in formulating strategies to enhance academic outcomes and provide targeted support to students.

## Analysis and Techniques Employed:

- **Exploratory Data Analysis (EDA)**: Initial exploration was performed to understand the dataset's distribution, detect outliers, and recognize patterns that might influence student performance.

- **Linear Regression**: A baseline model, linear regression was used to establish initial predictions and understand the weightage of different predictors on the performance index.

- **Ridge Regression**: Recognizing multicollinearity and overfitting concerns, Ridge Regression was applied. This regularization technique penalizes large coefficients to ensure model generalization.

- **Lasso Regression**: Lasso Regression was employed to induce feature selection. By penalizing non-important features and driving their coefficients to zero, Lasso aids in creating a simpler model.

- **Elastic Net**: As a middle ground between Ridge and Lasso, Elastic-Net was used. It combines penalties from both Ridge and Lasso, offering a balanced approach to handle multicollinearity, outlier effects, and irrelevant predictors.

- **Regression Analysis**: A comprehensive regression analysis was conducted to decipher the statistical significance of predictors, study residuals, and ensure the model's assumptions are met.

## Conclusion:

Academic performance is a confluence of numerous factors. Through rigorous modelling and analysis, this project provides insights into the relative importance of various predictors in determining academic success. These findings pave the way for educational stakeholders to develop informed interventions, ensuring every student achieves their full academic potential.
