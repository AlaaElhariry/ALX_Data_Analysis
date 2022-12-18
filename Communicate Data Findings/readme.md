# Prosper loans dataset Investigation

## by Alaa Elhariry


## Dataset Overview

This dataset contains data about Prosper, a credit company that facilitates peer-to-peer lending. There are 113,937 loans in total, with 81 different variables. I've used the following factors to conduct my investigation: Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate, Recommendations, and Investors are some of the terms used by Prosper.


## Summary of Findings

- The distribution of Prosper ratings is roughly normally distributed. Because this is obviously based on borrowers' self-reporting, there are a lot of outliers and a wide range of numbers, I believe there are a lot of erroneous values, therefore we'll wrestle with it below. I didn't think any scale transformations would be useful in this situation. The majority of loans are under $15,000, and it appears that the majority of loans are in 5,000-dollar increments. The prosper rating D is the most common rating among defaulted credits.

- Individuals with poorer credit ratings are more likely to receive default credits, as expected. The categories of business and home improvement appear to be more risky. For defaulted credits, the borrower rate is usually higher. Credits with a 60-month maturity are riskier than those with a shorter maturity (12 months). Individuals with a bad credit rating have a higher rate of borrowing. A better rating is associated with a larger monthly revenue. Individuals with lower ratings are more likely to be unemployed, self-employed, retired, or working part-time.


- For all Prosper ratings except the lowest, Defaulted credits are larger than Completed.


## Key Insights for Presentation


For the presentation, I chose important charts with a high data-to-ink ratio. The plots I chose depict the distribution of key factors such as loan status, monthly income, and Prosper rating, and I attempted to convey a story about the important predictors of loan status and Prosper rating variables.