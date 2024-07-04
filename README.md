# Exploratory_Data_Analysis
## Description  This project performs an exploratory data analysis (EDA) on a loan approval dataset. The analysis includes data cleaning, descriptive statistics, visualizations, and correlation analysis to identify key factors influencing loan approvals. 
# Loan Approval Status - Exploratory Data Analysis (EDA)

This repository contains the exploratory data analysis (EDA) for the loan approval status dataset. The analysis is performed using an R Markdown file (`EDAtest.Rmd`), which includes data visualization and statistical summaries to understand the patterns and factors affecting loan approvals.

## Project Overview

The objective of this project is to analyze the loan approval status dataset and gain insights into the factors that influence the approval of loans. The EDA will help in identifying the key variables that play a significant role in the decision-making process of loan approvals.

## Dataset

The dataset used for this analysis contains information on various loan applicants, including their demographic details, loan details, and approval status. The main features of the dataset include:

- **Applicant Income**
- **Coapplicant Income**
- **Loan Amount**
- **Loan Amount Term**
- **Credit History**
- **Gender**
- **Marital Status**
- **Dependents**
- **Education**
- **Self_Employed**
- **Property_Area**
- **Loan_Status**

## EDA Highlights

The EDA performed in this project includes:

1. **Data Cleaning:** Handling missing values, data type conversions, and outlier detection.
2. **Descriptive Statistics:** Summarizing the dataset to understand the distribution of variables.
3. **Visualizations:** Creating various plots (e.g., histograms, bar plots, box plots) to visualize the relationships between features and the loan approval status.
4. **Correlation Analysis:** Identifying the correlations between different variables and the loan approval status.

## How to Run the EDA

To run the EDA analysis, you need to have R and RStudio installed on your machine. Follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/parimal@7551/loan-approval-eda.git
    cd loan-approval-eda
    ```

2. Open `EDAtest.Rmd` in RStudio.

3. Knit the R Markdown file to generate the HTML report:
    ```r
    rmarkdown::render("EDAtest.Rmd")
    ```

## Results and Insights

The EDA reveals several important insights about the factors affecting loan approvals, such as:

- **Applicant Income** and **Coapplicant Income**: Higher incomes are associated with higher chances of loan approval.
- **Credit History**: Applicants with a good credit history have a significantly higher probability of loan approval.
- **Loan Amount**: The loan amount requested is also a critical factor, with higher amounts having lower approval rates.
- **Demographic Factors**: Factors such as gender, marital status, and property area also show varying impacts on loan approval status.

## Conclusion

This EDA provides a comprehensive understanding of the loan approval dataset and highlights the key factors influencing loan approvals. The insights gained from this analysis can be used to build predictive models for loan approval.

## Contact

For any questions or suggestions, please contact:

- **Parimal Bera**
- **Email:** parimalbera244@gmail.com

