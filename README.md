# lending-club-case-study
Lending Club, a marketplace for consumer finance that focuses on offering a range of loan products to urban customers, faces a significant challenge in managing its loan approval process. In assessing loan applications, the company must make informed decisions to reduce financial losses, which mainly stem from loans granted to applicants deemed "high-risk."

The primary goal of this analysis is to help Lending Club reduce credit losses. This issue arises from two potential scenarios:

Identifying applicants who are likely to repay their loans is essential, as they can generate profits for the company through interest payments. Rejecting such applicants would lead to missed business opportunities.
Conversely, approving loans for applicants unlikely to repay and at high risk of default could result in significant financial losses for the company.

## Insights Generated

- **Small Business Loans**: Loans provided for the purpose of 'small business' have a higher likelihood of default.
  
- **Annual Income**: Loans provided to users with an annual income of less than $20k have a higher likelihood of default.
  
- **Debt-to-Income (DTI)**: Loans given to applicants with a higher DTI have a higher likelihood of default.
  
- **Year-End Loans**: Loans issued at the end of the year have a higher chance of default.
  
- **Employee Length**: Applicants without a recorded employee length have a higher percentage of default.

- **Annual Income**:  Annualincome contains highly skewed data, so removed the records which has a higher annual income for analysis.

- **Grade analysis**: Grades with B and C has a higher likelihood of default

- **Loan amount**: Loan amount greater than 20k has a higher chance of default.


## Setup & Installation

Follow these steps to set up and run the analysis:

1. Clone the repository:
   ```bash
   git clone https://github.com/kiransunkari/lending-club-case-study.git
