# Project : Predicting Employee Churn

## Overview
The HR department at Salifort Motors need to improve employee satisfaction. They collected satisfaction data on employees and need help to analyze the data and check what is likely to make the employees leave the company.

## Problem
There is a high turnover in the company and HR department whoul like to understand what factors drive the likelihood that employees leave the company. 

## Solution
Built a logistic regression to predict whether or not an employee will leave the company. 

## Summary results
Logistic regression offers a good way to tackle the problem. There appears to be a good statistical relationship between several variables and the outcome of interest (whether an employe is likely to leave or not). Out of four logistic regression modeling attempts, the one with up-sampling and outliers deletion yield de best results overall, with an F1 score of 0.640. While this model's precision is low (0.488), its recall is particularly high (0.928), which means that models is very accurate when it comes to predicting those who will actually leave the company, but more than half of those predicted to leave, will not leave in the end.
From the coefficients of the model, it appears that some variables are negatively associated with the log-odd of leaving the company, while other variables are positively associated with the log-odd of leaving the company. And the directions of those relationships make sense intuitively. For instance, the more the satisfaction level, the less likely an employee is to leave the country, and an employee with a low salary is more likely to leave the company than an employee of high salary.

## Recommandation / Next steps
Working to improve employee satisfaction could help retain employees. It is also recommended to avoid not promoting employees for a too long period. The company should investigate to see why employees in Sales department and Support department seem more likely to leave than others. It is also worth refining the data and studying resignations and dismissals separately.




