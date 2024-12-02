# Graduate Admission Prediction: Linear Regression Analysis

## Project Overview

This project is a data science case study for Jamboree Education, focusing on predicting the chances of graduate admission using linear regression. The goal is to develop a predictive model that helps students understand their probability of getting into top colleges, particularly from an Indian perspective.

### Business Context

Jamboree Education assists students in preparing for standardized tests like GMAT, GRE, and SAT. This project extends their services by providing a data-driven approach to estimating graduate admission probabilities.

## Dataset

The dataset contains information about graduate school applicants with the following features:
- Serial No. (Unique row ID)
- GRE Scores (out of 340)
- TOEFL Scores (out of 120)
- University Rating (out of 5)
- Statement of Purpose and Letter of Recommendation Strength (out of 5)
- Undergraduate GPA (out of 10)
- Research Experience (0 or 1)
- Chance of Admit (ranging from 0 to 1)

## Project Methodology

### Key Techniques Used
- Exploratory Data Analysis (EDA)
- Linear Regression
- Statistical Model Validation

### Analysis Steps
1. Data Preprocessing
   - Handling missing values
   - Checking for duplicates
   - Outlier treatment
   - Feature engineering

2. Exploratory Data Analysis
   - Univariate analysis
   - Bivariate analysis
   - Distribution and relationship exploration

3. Linear Regression Modeling
   - Model building using Statsmodel library
   - Coefficient interpretation
   - Model performance evaluation

4. Model Validation
   - Multicollinearity check (VIF)
   - Residual analysis
   - Assumption testing
     - Mean of residuals
     - Linearity
     - Homoscedasticity
     - Normality of residuals

5. Performance Metrics
   - Mean Absolute Error (MAE)
   - Root Mean Square Error (RMSE)
   - R-squared
   - Adjusted R-squared

## Key Insights and Recommendations

*(Replace this section with your actual findings from the analysis)*

- Identified most significant predictors of admission chances
- Highlighted potential improvements for the predictive model
- Suggested additional data sources for model enhancement

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Seaborn

## How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/graduate-admission-prediction.git
```

2. Install required dependencies
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook
```bash
jupyter notebook Graduate_Admission_Analysis.ipynb
```

