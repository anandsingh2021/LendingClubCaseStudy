# Lending Club Case Study

> This project analyzes Lending Club's loan dataset to identify key factors contributing to loan defaults, enabling better risk assessment and lending strategies.

---

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

---

## General Information
- **Objective:** Minimize financial risk by analyzing historical loan data and identifying patterns associated with loan defaults.
- **Dataset:** Lending Club loan dataset (2007–2011), containing borrower demographics, loan details, and repayment statuses.
- **Business Problem:** 
  - **Loss of Business:** Denying loans to creditworthy borrowers.
  - **Financial Loss:** Approving loans for high-risk borrowers likely to default.
- **Approach:**
  - Data cleaning and preparation.
  - Univariate and bivariate analysis to explore key patterns.
  - Visualization of insights to inform actionable recommendations.

---

## Technologies Used
- Python - version 3.12.4
- Matplotlib - version 3.8.4
- Seaborn - version 0.13.2
- Numpy - version 1.26.4
- Pandas - version 2.2.2

---

## Insights
- The 'Loan Amount Bucket' of 5K - 10K have highest 'Charged Off' loans. The absolute no's of "Charged Off" loans gradually fall as we go to higher "Loan Amount Buckets"

- Whereas the absolute no of "Charged Off" loans are highest in the 'Loan Amount Bucket' of 5K - 10K and then gradually decline as we go up. However, when expressed as a percentage - "Charged Off" loans as a percentage of total loans in the respective Loan Amount Bucket -     # The percentage of Charged Off Loans go up as the Pardue Loan Amount Bucket increases

- Given the larger base the high absolute However, are experienced for Charged Off Loans in lower loan tenure i.e. 36 months. However, "Charged Off" loans as a percentage of total loans for the respective tenures are higher for higher tenures i.e. in 60 months tenure

- Percentage of Charged Off loans increases as the Interest Rate increases.

- Percentage of Charged Off loans increases as the Grade increases from 'A' to 'G'

- No clear evidence to suggest that emp_lenth has an impact on loans that are charged off

- Annual Income has a very significant impact on the Charged Off Loan. We experience high Charged Off loans in lower Annual Income brackets and they go down significantly as the Annual Income increases

- Charged off loans as a percentage of Total Loans is highest where the purpose of the loan is for Small Business

- Annual Income has a very significant impact on the Charged Off Loan. Charged off loans as a percentage of Total Loans is significantly high for AK, NV and TN and the lenders needs to be cognizant of that

- Charged off loans as a percentage of Total Loans is shows an increase as the DTI increases. The increase starts from bucket '4-6' and peaks in the DTI bucket of '20-22' and the gradually tapering down again

- Charged off Loans as a percentage goes up significantly as the number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years exceeds 7

- Charged off Loans as a percentage goes up significantly as the number of inquiries in past 6 months (excluding auto and mortgage inquiries) exceeds 5

- Not really a very strong relationship but charged off Loans as a percentage goes up significantly as the number of open credit lines in the borrower's credit file exceeds 30

- Charged off loans as a percentage goes up significantly as the number of derogatory public records is more than '0' and goes up as we increase from '1' to '2'

- Charged off Loans as a percentage goes up significantly as the number of public record bankruptcies increases significantly as it increases from 0' to '1' and then again to '2'

# Recommendations
- Strengthen risk assessments for 5K-10K loans and high loan brackets to reduce defaults.
- Implement stricter policies for 60-month loans due to higher default rates; encourage shorter tenures.
- Review high-interest rate tiers and provide financial counseling to borrowers.
- Enhance credit evaluations for grades E, F, and G; incentivize risk-based pricing.
- Prioritize other attributes as employment length has minimal impact.
- Address risks in the "Other" ownership category to reduce defaults.
- Focus on low-risk loans for higher incomes; support low-income borrowers with financial literacy.
- Monitor small business loans closely and strengthen credit checks for high-risk purposes.
- Enforce stricter lending for DTI ratios of 20-22 and high delinquencies.
- Limit inquiries and closely evaluate borrowers with over 30 open credit lines.
- Monitor borrowers with multiple derogatory records and bankruptcies more stringently.

---

## Acknowledgements
- **Data Source:** Lending Club dataset provided for the case study.
- **Inspiration:** This project is part of an academic program on Exploratory Data Analysis (EDA) and risk analytics.
- **Tutorials and Guidance:** Insights drawn from course materials and online resources.
- This project was inspired by live session of upGrad on EDA by Akash Garg
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

---

## Contact
- Created by **Anand Singh**   & **Deepali Pardhe**
- Feel free to contact for further details or collaboration opportunities.

---

