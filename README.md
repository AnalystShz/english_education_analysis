### English Education Performance Analysis – A Data Analytics Case Study

I am excited to present my English Education Performance Analysis project. Through exploratory data analysis, statistical testing, and predictive modeling, I have uncovered meaningful insights into the factors influencing education performance across towns in England.
This project demonstrates my ability to clean, analyze, model, and interpret structured data to generate actionable insights that support data-driven decision-making in the public sector.

Author: Shezmin Rahim
Date: February 2026

## Tools

Python (Pandas, NumPy)
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

## Scenario

You are a Junior Data Analyst working with a regional education policy team in England. The government wants to understand what factors influence education performance across towns and whether there are structural differences based on town size, region, and early academic outcomes.
The goal is to identify:
Key drivers of education performance
Differences between small and large towns
Predictors of long-term academic success
Areas requiring policy intervention
The executive education board will review the findings, so all insights must be backed by statistical analysis and clear visualizations.

# Stakeholders
Primary Stakeholders
Regional Education Policy Board
Department for Education strategic planners

# Secondary Stakeholders

Local councils
Education funding allocation teams
School performance analysts

## About the Dataset
The dataset contains town-level education performance metrics across England.

## Key attributes include:

town_name
region
town_size
population
ks2_2007_08
ks4_2012_13
activity_19_further_edu
activity_19_apprenticeships
education_score

The dataset was structured and analysis-ready but required cleaning and validation.

## This Project Follows the 6-Step Data Analysis Process

Ask
Prepare
Process
Analyze
Share
Act

## Ask
Business Task
What factors most strongly influence education performance across towns in England?

Key Questions
Do small towns outperform large towns?
Are early academic results predictive of later performance?
Does population size impact outcomes?
Are there regional disparities?
What variables are strongest predictors of education score?

## Prepare
Data Source
Publicly available structured education dataset containing town-level academic metrics.
Data Storage and Organization
CSV format
Imported into Jupyter Notebook
Analyzed using Pandas DataFrames
Data Integrity

The dataset was evaluated for:
Missing values
Duplicates
Outliers

Data type consistency
The dataset was considered reliable and suitable for analysis after cleaning.

## Process
Data Cleaning and Transformation (Python)
Removed duplicates
Handled null and missing values
Verified numeric data types
Standardized column names
Checked for outliers
Created summary statistics
Feature Engineering
Grouped data by town size
Created correlation matrix
Segmented high vs low performing towns
Prepared feature set for regression modeling

## Analyze

In this stage, I performed:

01. Exploratory Data Analysis

Distribution of education scores
Town size comparison
Regional breakdown
Population vs education score analysis

02. Correlation Analysis

A correlation matrix revealed:
Strong relationship between KS2 and KS4 performance
Early academic attainment is highly predictive of later outcomes
Population size showed weaker correlation with education score

03. Statistical Testing

A t-test was performed to determine whether small and large towns differ significantly in education performance.

Result:
The difference between small and large towns was statistically tested.
Interpretation focused on whether town size alone drives performance.

04. Predictive Modeling

A Linear Regression model was built to predict education_score.

Model insights:

KS2 and KS4 results were the strongest predictors.
Apprenticeship and further education participation showed moderate impact.
Population had limited predictive power.
R² score evaluated model effectiveness.
Share – Key Findings
Early academic performance (KS2) strongly predicts later education outcomes.
KS4 attainment is a major driver of overall education score.
Town size alone is not a dominant factor in performance.
Some regional disparities suggest unequal distribution of educational success.
Population size does not strongly determine education outcomes.
Apprenticeship and further education participation moderately influence town-level education performance.

Visual Insights
The analysis included:
Correlation heatmap
Town size comparison bar charts
Population vs education scatter plots
Top and bottom performing towns
Regression evaluation metrics
(Visualizations available in the Jupyter Notebook.)

Act – Recommendations
Based on the findings:

01. Invest in Early Education
Since KS2 strongly predicts long-term outcomes, early-stage intervention programs should be prioritized.

02. Strengthen Secondary School Support
KS4 attainment significantly impacts overall education performance. Additional funding or policy focus at this stage may yield strong improvements.

03. Avoid Oversimplified Town-Size Policies
Performance differences are not solely determined by town size. Policies should focus on educational structure rather than population scale.

04. Target Underperforming Regions
Regional disparity analysis suggests some areas require focused resource allocation.

05. Improve Apprenticeship & Further Education Pathways
Encouraging structured post-16 pathways may positively influence town-level outcomes.

## Project Skills Demonstrated

Data Cleaning & Validation
Exploratory Data Analysis
Statistical Testing (t-test)
Correlation Analysis
Predictive Modeling (Linear Regression)
Business Insight Development
Policy-Oriented Recommendations
Data Visualization


Conclusion
This project demonstrates how structured data analysis can uncover meaningful insights within the education sector. By identifying key predictors of education performance and validating findings with statistical methods, this analysis supports evidence-based policy decision-making.
The findings highlight the importance of early academic investment, structured secondary education support, and data-driven regional intervention strategies.

