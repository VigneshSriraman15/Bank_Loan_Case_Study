# Bank_Loan_Case_Study :-

## Introduction :

· The dataset provided contains the information about loan applications. It includes two types of scenarios:

    1. Customers with payment difficulties: These are customers who had a late payment of more than X days on at least one of the first Y installments of the loan.

    2. All other cases: These are cases where the payment was made on time.

· When a customer applies for a loan, the company faces two risks:

    1. If the applicant can repay the loan but is not approved, the company loses business.

    2. If the applicant cannot repay the loan and is approved, the company faces a financial loss.

· This project aims to carry out Exploratory Data Analysis (EDA) to analyze patterns in the data and ensure that capable applicants are not rejected.

## Data Cleaning :

· Handle Missing Values: Identify and address missing values through imputation, removal, or other techniques.

· Remove Duplicates: Identify and eliminate duplicate records if necessary.

· Correct Errors: Fix inaccuracies or inconsistencies in the data.

· Standardize Formats: Ensure that data formats are consistent (e.g., date formats, text casing).

## Tools & Technologies Used :

· Microsoft Excel (2019) & it's functions and forumulas.

## KPI's :

### 1) Identify Missing Data and Deal with it Appropriately:

 · Identified the missing data in the dataset using Excel built-in functions and features.
 
 · Utilized Excel functions like COUNT, ISBLANK, and IF to identify missing data and used functions like AVERAGE or MEDIAN for imputation or other appropriate methods available in Excel.

 · Visualized the final data set representing the count of blank cells for each column using bar chart.

### 2) Identify Outliers in the Dataset:

 · Outliers can significantly impact the analysis and distort the results, identified the outliers in the dataset using Excel statistical functions and features, focusing on numerical variables.

 · Utilized excel functions like QUARTILE, IQR, and conditional formatting to identify the potential outliers and visualized the same using box plot.

### 3) Analyze Data Imbalance:

 · Data imbalance can affect the accuracy of the analysis, especially for binary classification problems. Understanding the data distribution is crucial for building reliable models.

 · Calculated the proportion of each variable for all the categorical columns and visualized it using pie chart.

### 4) Perform Univariate, Segmented Univariate, and Bivariate Analysis:

 · Performed univariate analysis to understand the distribution of individual variables, segmented univariate analysis to compare variable distributions for different scenarios, and bivariate analysis to explore relationships between variables and the target variable using excel functions and features.

 · Utilized excel functions like COUNT, AVERAGE, MEDIAN, and statistical functions for descriptive analysis and utilized excel features like filters, sorting, and pivot tables for segmented and bivariate analysis.

 · Created a horizontal bar chart to visualise the results.

### 5) Identify Top Correlations for Different Scenarios:

 · Segmented the dataset based on different scenarios (e.g., clients with payment difficulties and all other cases) and identified the top correlations for each segmented data using excel functions.

 · Utilized excel functions like CORREL to calculate correlation coefficients between variables and the target variable within each segment and ranked the correlations to identify the top indicators of loan default for each scenario.

## Conclusion :

· This project has identified the patterns that indicate if a customer will have difficulty paying their installments. This information can be used to make decisions such as denying the loan, reducing the amount of loan, or lending at a higher interest rate to risky applicants.

· The case study on bank loan data has provided a comprehensive overview of lending patterns, repayment behavior, and default rates. Our analysis has highlighted key factors influencing loan performance and identified trends that impact both loan approval and risk management processes.

· To improve operational efficiency, the study suggests streamlining the loan approval process by incorporating automated risk assessment tools. This could reduce processing time while ensuring a more thorough evaluation of potential risks.

