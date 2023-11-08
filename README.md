# Project Name
> * Assignment : Lending Club Case Study
> * (Team : Aswin J Shaji & Lokesh Gaddam )
> * Group Facilitator : Name: Aswin J Shaji
> * Team Member Detail: Name: Lokesh Gaddam
> * Date : 8 Nov 2023


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> ### Business Understanding :
> Lending Club is a financial institution that specializes in offering different loan types to urban clientele. Upon receiving a loan application, the company needs to evaluate the applicant's profile to decide on loan approval. 
> This decision involves managing two types of risks:
> Denying the loan to a potentially creditworthy applicant results in a loss of business for the company.
> Approving a loan for an applicant at risk of defaulting may lead to financial loss for the company.
> 
> ### Objective:
> The company aims to comprehend the key factors influencing loan default (specifically, when the loan_status = 'Charged Off'), referring to the robust indicators that strongly correlate with defaults. This understanding can be employed by the company for portfolio management and assessing risks.
> 
> The data set that is used for this purpose is loan.csv


## Conclusions
> ### EDA Summary 
> * Observation on Grades: Loan applicants falling within grades B, D, and C demonstrate higher defaulter rates compared to other grade categories.
> * Term Impact on Defaulting: Loan applicants with a term of 36 months show a higher likelihood of defaulting.
> * Employment Length and Defaulting: Applicants with a tenure of 10 years in employment are more prone to defaulting. However, this contradicts the typical understanding that longer job experience correlates with higher annual income and lower default rates. Bivariate analysis is necessary to explore this in conjunction with other factors for deeper insights.
> * Verification Status and Default Probability: Applicants who have not been verified exhibit a higher chance of default. However, verified status also shows a proximity to defaulters, necessitating further analysis with additional columns for comprehensive insights.
> * Loan Purpose and Default Probability: Applicants intending to clear other loans or consolidate debts are more susceptible to defaulting.
> * Home Ownership and Defaulting Probability: Those who rent their homes have the highest likelihood of defaulting on a loan, followed by applicants with mortgages.
> * Annual Income, Purpose, and Defaulting: Applicants earning an annual income between $60,000 and $70,000, seeking loans for home improvements, tend to default in higher numbers, followed closely by those seeking loans for small businesses, credit cards, and weddings.
> * Annual Income and Home Ownership Impact on Defaulting: Applicants with an annual income of $60,000 to $70,000 and with mortgages are the most frequent defaulters.
> * Loan Amount and Home Ownership Impact on Defaulting: Applicants owning homes with mortgages and having loans within the range of $13,000 to $14,000 show a propensity for defaulting.
> * Loan Amount and Purpose Impact on Defaulting: Borrowers seeking loan amounts between $11,000 and $14,000 for small business purposes exhibit a higher rate of defaulting, followed by those seeking loans for credit cards and debt consolidation.
> * Loan Amount and Employee Length Impact on Defaulting: Borrowers with a decade of work experience, borrowing between $13,000 and $14,000, tend to default on their loans.
> * Relationship between Grade and Interest Rate: Grading, used by banks to evaluate borrowers from A to F, influences interest rates. Interest rates rise with a shift from A to F, indicating that higher-graded applicants receive lower rates. This increase in grade and interest rates corresponds with a higher likelihood of default, particularly in credit card and debt consolidation defaults.
> * Loan Status in Relation to Interest Rates: There's an observable trend in defaulters as interest rates exceed 11%, further increasing as it surpasses 14%.
> ### Additional summary using IV and WOE
> * Shorter loan terms associate with a decreased likelihood of default.
> * Higher credit grades (above B5) correspond to reduced default probabilities, with an inverse relationship—higher grades indicate lower default chances.
> * Verified income is linked to a lower likelihood of default.
> * Ideal loan purposes with lower default chances include weddings, major purchases, and credit cards.
> * Following closely, car loans, home improvement, and vacation purposes exhibit lower default probabilities.
> * States with the most favorable customers include WY, DC, MS, DE, VT, AR, TN, TX, KS, AL, MA, WV, and PA.
> * Longer loan terms are associated with an increased likelihood of default.
> * Lower credit grades (below C1) are likely to result in defaults, with a higher chance of defaulting as the grade decreases.
> * Unverified income correlates with a higher chance of default.
> * Loans intended for funding small businesses represent the least favorable purposes in terms of default probability.
> * States with less desirable customers in terms of default likelihood include NE, NV, SD, AK, FL, HI, MO, NM, ID, OR, and CA.
> * The interest rate for the loan plays a significant role in default probability; lower interest rates correlate with a reduced chance of default.
> * Optimal interest rate: Below 8% offers the lowest default likelihood, while below 10% stands as the next favorable option.
> * Higher income levels are associated with a decreased likelihood of default.
> * A lower credit utilization percentage is linked to a reduced chance of default.
> * The interest rate for the loan greatly impacts the chance of default; higher interest rates correspond to an increased probability of default.
> * Loans above 14% pose a high chance of default and should be avoided.
> * Lower income levels are linked to a higher probability of default.
> * Higher credit utilization percentages are associated with an increased chance of default.
> * A higher likelihood of default is indicated if more than 2 inquiries have been made in the last 6 months.




## Technologies Used
> - Jupyter note book v2.5.0
> - python3
> - Libraries: numpy, pandas, seaborn