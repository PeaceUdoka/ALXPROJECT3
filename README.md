# LoanDataFromProsper
## by Azubuogu Peace Udoka


## Dataset

The loan data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set.

The purpose of analysis was to find which features affected the outcome of a loan status and a few variables were chosen for this. Variables like APR were chosen instead of interest rate because APR is a more accurate picture of the cost of th loan. Prosper rating was also chosen because it took nto consideration a couple other variables like number of inquiries, number of deliquent accounts, prosper score, credit score, etc. which were excluded.

Analysis involved removing rows with missing values of APR and after exploration, I decided to focus on loans with defaulted and charged off status as these were most essential in a lenders' risk analyses or loss estimates.



## Summary of Findings

During exploration, I found that majority of loans recorded were either current, completed, charged off or defaulted. I decided to focus on the defaulted and charged off loans. 

To understand why lenders would charge off loans, I explored the relationship between charged off loans and ontimepayments. These loans which were majorly of small amounts were associated with a higher range of total prosper loans and on time payments. This could explain why lenders charged them off.

For defaulted loans, exploration showed that majority of the loans were also of small amounts but with a record of few total prosper loans and fewer range of on time payments. 

I also observed that some borrowers were unemployed. Further exploration showed that these unemployed borrowers owned homes and completed their loans. A good amount of them also had their loans charged off despite the high APR, and these were loans of small amounts.

Also, being a home owner aand a member of a group had little to no effect to the status of loans



## Key Insights for Presentation
For the presentation, I focused on the effects of APR, Loan original amount and ontime payments for charged off loans of unemployed borrowers.

First, I showed how a good number of borrowers were unemployed and had their loans charged off. I tried to explain this incident by showing these charged loans with high APRs are associated with low Prsoper Ratings and were also loans of small amounts. Then, i explained that in addition to all these, charged off loans had a higher record of total prosper loans and on time payments.