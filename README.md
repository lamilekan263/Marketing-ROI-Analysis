````markdown
# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview

This project analyzes the relationship between marketing expenditures and sales performance using Simple Linear Regression. The objective is to identify which marketing channel (TV, Radio, or Social Media) has the strongest impact on sales and provide data-driven recommendations for marketing budget allocation.

The analysis follows a complete data science workflow, including data cleaning, exploratory data analysis (EDA), model development, diagnostic testing, and business interpretation.

## Project Objectives

- Load and clean the marketing dataset.
- Explore relationships between advertising channels and sales.
- Identify the marketing channel most strongly correlated with sales.
- Build a Simple Linear Regression model using Ordinary Least Squares (OLS).
- Validate regression assumptions through diagnostic plots.
- Interpret model outputs in a business context.
- Recommend the most effective marketing channel for future investment.

## Dataset

The dataset contains the following variables:

| Variable | Description |
|----------|-------------|
| TV | TV advertising budget |
| Radio | Radio advertising budget |
| Social Media | Social media advertising budget |
| Sales | Product sales |

## Project Structure

```text
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
````

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* SciPy
* Jupyter Notebook

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd marketing-roi-regression
```

### Create and Activate a Virtual Environment (Optional)

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
```

Or install from the requirements file:

```bash
pip install -r requirements.txt
```

## Analysis Workflow

### 1. Data Preparation

* Load the dataset
* Inspect data types and structure
* Handle missing values
* Verify data quality

### 2. Exploratory Data Analysis (EDA)

* Generate summary statistics
* Analyze correlations
* Create scatter plots
* Create pair plots
* Visualize relationships using heatmaps

### 3. Variable Selection

The advertising channel with the highest correlation to **Sales** is selected as the independent variable for the Simple Linear Regression model.

### 4. Model Development

Build an Ordinary Least Squares (OLS) regression model using the `statsmodels` library.

### 5. Model Validation

Evaluate regression assumptions using:

* Residual vs Fitted Plot (Linearity)
* Histogram of Residuals (Normality)
* Q-Q Plot (Normality)
* Scale-Location Plot (Homoscedasticity)

### 6. Business Interpretation

Interpret the following metrics:

* **R-squared** – Measures the proportion of variance explained by the model.
* **Regression Coefficient** – Indicates the expected change in sales for a one-unit increase in advertising spend.
* **P-value** – Determines whether the relationship is statistically significant.

## Key Findings

* The marketing channel with the strongest correlation to sales was selected as the predictor variable.
* The regression model quantified the relationship between advertising spend and sales performance.
* Statistical significance was assessed using p-values.
* Diagnostic plots were used to validate model assumptions.

## Business Recommendation

Based on the regression results, marketing resources should be allocated toward the advertising channel that demonstrates the strongest statistically significant relationship with sales. Prioritizing investment in this channel can improve marketing ROI and support more effective budget allocation decisions.

## Future Improvements

* Build a Multiple Linear Regression model using all advertising channels.
* Perform feature engineering and transformation.
* Apply cross-validation techniques.
* Conduct marketing mix optimization.
* Explore sales forecasting using time-series models.

## Author

**Kunle**

## License

This project is intended for educational and portfolio purposes.

```
```
