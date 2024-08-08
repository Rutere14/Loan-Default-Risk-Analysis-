
# Loan Default Risk Analysis 


## About
This project focuses on analyzing loan default risk with Python, using a dataset containing customer demographics, loan details, and historical default information, likelihood of a customer defaulting on a loan based on various factors such as income, credit history, loan purpose, and interest rates By analyzing these variables, the project aims to provide insights that can help financial institutions make more informed lending decisions, reduce default rates, and better manage risk. The project involves data preprocessing, exploratory data analysis, feature engineering, statistical analysis and data visualization.




## Objectives 

1. **Data Exploration:** Uncover insights into the financial behaviors and demographics of respondents in the dataset.

2. **Descriptive Statistics:** Provide a detailed overview of key indicators such as age, income, employment duration, and loan interest rate among the surveyed population.

3. **Analyze customer demographics:**   Financial details, credit history, and loan characteristics to identify key indicators of default risk.

4. **Provide  Insights:**   Help financial institutions improve their risk management strategies.

5. Reduce the rate of loan defaults through data-driven analysis.

6. Assist in making more informed lending decisions.



## Key Findings

By analyzing various factors such as customer demographics, financial details, credit history, and loan characteristics, the project aims to identify key indicators of loan default risk. The ultimate goal is to provide insights that can help financial institutions improve their risk management strategies, make more informed lending decisions, and reduce the rate of loan defaults.

## About the Data 
This dataset contains information about customer loans, including customer demographics, loan details, and default status. The data contains 13 columns and 32,586 rows:

| Column               | Description                                                          | Data Type  |
|----------------------|----------------------------------------------------------------------|------------|
| `customer_id`        | Unique identifier for each customer                                  | `float64`      |
| `customer_age`       | Age of the customer                                                  | `int64`      |
| `customer_income`    | Annual income of the customer                                        | `object`      |
| `home_ownership`     | Home ownership status (e.g., RENT, OWN, MORTGAGE)                    | `object`   |
| `employment_duration`| Duration of employment in months                                     | `float64`      |
| `loan_intent`        | Purpose of the loan (e.g., PERSONAL, EDUCATION, MEDICAL, VENTURE)    | `object`   |
| `loan_grade`         | Grade assigned to the loan                                           | `object`   |
| `loan_amnt`          | Loan amount requested                                                | `float64`    |
| `loan_int_rate`      | Interest rate of the loan                                            | `float64`    |
| `term_years`         | Loan term in years                                                   | `int64`      |
| `historical_default` | Indicates if the customer has a history of default (Y/N)             | `object`   |
| `cred_hist_length`   | Length of the customer's credit history in years                     | `int64`      |
| `Current_loan_status`| Current status of the loan (DEFAULT, NO DEFAULT)                     | `object`   |


## Questions to answer

### Descriptive Statistics

1. What is the average loan amount requested by customers?
2. What is the median customer income?
3. What is the distribution of loan grades?
4. What is the average interest rate for loans?
5. What is the average credit history length(years) of customers?

### Aggregations and Grouping

6. What is the average loan amount by loan intent?
7. What is the average interest rate by home ownership status?
8. What is the average customer age by loan grade?

### Filtering and Conditional Queries

9. What is the average income of customers who defaulted on their current loan?

### Correlation and Relationships
10. Is there a correlation between customer income and loan amount?

## Insights
1. people renting their homes account for the highest number of defaulters while people who won account for the least.
2. Education was the main reason why people took up loans and home improvement was the last reason.
3. Loan grade A was the most popular with the highest distribution of 15,141.
4. There were more people with a history of default compared to those who had not defaulted.
5. The current loan status data shows that there are fewer defaulters compared to non-defaulters.
6. The majority of our customer base falls within the age range of 20 to 40 years.

## Tools Used
- Python
