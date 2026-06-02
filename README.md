Marketing ROI Analysis Using Simple Linear Regression
Project Overview

This project analyzes the relationship between marketing expenditures and sales performance using Simple Linear Regression. The objective is to identify which marketing channel (TV, Radio, or Social Media) has the strongest impact on sales and provide data-driven recommendations for marketing budget allocation.

The analysis follows a complete data science workflow, including data cleaning, exploratory data analysis (EDA), model development, diagnostic testing, and business interpretation.

Project Objectives
Load and clean the marketing dataset.
Explore relationships between advertising channels and sales.
Identify the marketing channel most strongly correlated with sales.
Build a Simple Linear Regression model using Ordinary Least Squares (OLS).
Validate regression assumptions through diagnostic plots.
Interpret model outputs in a business context.
Recommend the most effective marketing channel for future investment.
Dataset

The dataset contains the following variables:

Variable	Description
TV	TV advertising budget
Radio	Radio advertising budget
Social Media	Social media advertising budget
Sales	Product sales
Project Structure
marketing-roi-regression/
│
├── data/
│   └── marketing.csv
│
├── notebooks/
│   └── regression_analysis.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Statsmodels
SciPy
Jupyter Notebook
Installation

Clone the repository:

git clone <repository-url>
cd marketing-roi-regression

Create and activate a virtual environment (optional):

python -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

Install dependencies:

pip install -r requirements.txt
Analysis Workflow
1. Data Preparation
Load dataset
Inspect data types
Handle missing values
Verify data quality
2. Exploratory Data Analysis
Summary statistics
Correlation analysis
Scatter plots
Pair plots
Heatmaps
3. Variable Selection

The independent variable with the highest correlation to Sales is selected as the predictor for the regression model.

4. Model Development

An Ordinary Least Squares (OLS) Simple Linear Regression model is built using Statsmodels.

5. Model Validation

Regression assumptions are evaluated through:

Residual vs Fitted Plot (Linearity)
Histogram of Residuals (Normality)
Q-Q Plot (Normality)
Scale-Location Plot (Homoscedasticity)
6. Business Interpretation

The model's:

R-squared value
Regression coefficient
P-value

are interpreted to assess marketing effectiveness and return on investment (ROI).

Key Findings
The marketing channel with the strongest correlation to sales was selected for modeling.
The regression model quantified the expected increase in sales associated with increased advertising spending.
Statistical significance was evaluated using p-values.
Diagnostic plots were used to verify model assumptions.
Business Recommendation

Based on the regression analysis, marketing resources should be prioritized toward the advertising channel with the strongest statistically significant relationship to sales. This approach maximizes expected return on marketing investment and supports more efficient budget allocation.

Future Improvements
Multiple Linear Regression using all marketing channels.
Feature engineering.
Cross-validation techniques.
Marketing mix optimization.
Time-series forecasting of sales performance.
Author

Kunle

License

This project is for educational and portfolio purposes.