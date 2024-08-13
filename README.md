# Loan Default Risk Analysis

## Project Overview

This project focuses on exploring loan default risks for a consumer finance company that specializes in providing various types of loans to urban customers. The company needs to assess whether to approve or reject a loan application based on the applicant’s profile. This decision carries two types of risks:

1. **Loss of Business**: If a loan is not approved for an applicant who is likely to repay, the company loses potential business.
2. **Financial Loss**: If a loan is approved for an applicant who is likely to default, the company risks financial loss.

The aim of this project is to identify patterns that indicate whether an applicant is likely to default, enabling the company to make informed decisions regarding loan approvals, amounts, and interest rates.

## Project Components

### 1. Exploratory Data Analysis (EDA) Jupyter Notebook

The Jupyter Notebook contains a detailed exploratory data analysis of the loan application data. This analysis includes:

- **Data Cleaning**: Handling missing values, data types, and preprocessing.
- **Descriptive Statistics**: Summary statistics and distributions of key variables.
- **Data Visualization**: Graphical representations to identify patterns and relationships.
- **Feature Analysis**: Examination of variables affecting loan default, such as loan term, grade, loan amount, annual income, employment length, loan purpose, and interest rate.

### 2. PowerPoint Presentation

The PowerPoint presentation provides key insights and findings from the EDA. It includes:

- **Summary of Findings**: Key patterns and trends identified from the data analysis.
- **Driving Factors**: Detailed analysis of variables influencing loan defaults:
  - **Loan Term**: Higher default rates are associated with longer loan terms.
  - **Grade**: Higher risk is associated with high-risk loan grades.
  - **Loan Amount**: Increased loan amounts are linked to higher default rates.
  - **Annual Income**: Higher default rates are observed in lower income brackets.
  - **Employment Length**: Default rates are higher for applicants with very short or long employment histories.
  - **Loan Purpose**: Debt consolidation and credit card loans have higher default rates.
  - **Interest Rate**: Higher installment amounts correlate with higher default rates.

## Driving Factors (Key Insights)

1. **Loan Term**: The average interest rate for defaulted applications is notably higher for longer loan terms (12.38% for 36 months, 15.75% for 60 months).
2. **Grade**: Default rates are significantly higher among high-risk loan applicants. Careful vetting is necessary for such applications.
3. **Loan Amount**: Larger requested loan amounts are associated with a higher defaulter rate.
4. **Annual Income**: Applicants with annual incomes around $90K have a greater share of defaulted loans.
5. **Employment Length**: The highest number of defaulters have either 0-2 years or 10+ years of experience. This should be taken into account while processing loan applications.
6. **Loan Purpose**: Loans for debt consolidation and credit card purposes are more likely to default and should be scrutinized carefully.
7. **Interest Rate**: Higher installment amounts are associated with a higher rate of defaults.

## Usage

- **Jupyter Notebook**: Run the notebook to explore the data, perform analysis, and visualize results.
- **PowerPoint Presentation**: Review the presentation to understand the key insights and actionable findings from the EDA.

## Requirements

- Python 3.x
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels` libraries for the Jupyter Notebook
- PowerPoint software to view the presentation


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##contact me 
- email :akashanandani.56@gmail.com
- github -lashh56
