# Loan Dataset Exploration
## by Karim Henry


## Dataset

> This document explores a dataset containing amount, status , interest rate and other attributes for approximately 114,000 loans.

## Summary of Findings

> Monthly Payment is strongly correlated with original loan payment at 3 levels of loan period. for same loan amount, higher value of monthly payment  is seen for shorter period. The increase in monthly payment for same loan amount from 60  to 36 month is small compared to that between 36 and 12 month. 

> The interst rate depends on credit score and on loan period whereby interest rate decrease from nearly 0.29 at score of 620 to about 0.12 at score of 850 for 60 months also interest rate is at lower levels for shorter loan periods at the smae scores whereby we can see, for instance, interest rate decreasing from 0.15 to 0.11 ending with values below 0.10 as period declines from 60 to 36 ending with 12 months. Higher loan amounts above 27k take place at credit score of 720. Also, interest rate grades up towards higher credit scores.

> Completed loans are having greater AA grades with respect to other grades, in contrast to charged off and defaulted grades whereby AA grades are low compared to other grades. Non employed people are not allowed long loan periods of 60 months, with smaller loan amounts with a maximum of 6000 dollars.


## Key Insights for Presentation

> For the presentation, I tried to show the factors affecting interest rate and differences between different loan amounts and the ambiguity in predicting loan status for future clients depending only on these features. I tried to show features attributed to completed loans through different visualizations. 