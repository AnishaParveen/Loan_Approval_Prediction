***Loan Approval System***

This repository contains a dataset and code related to a loan approval system. The dataset includes information about loan applicants, such as loan ID, number of dependents, education level, employment status, income, loan amount, loan term, credit score (CIBIL score), and various asset values. The goal of the system is to predict whether a loan application should be approved or rejected based on these factors.

Dataset
The dataset (loan_approval_dataset.csv) includes the following columns:

loan_id: Unique identifier for each loan application

no_of_dependents: Number of dependents of the applicant

education: Education level of the applicant (Graduate/Not Graduate)

self_employed: Employment status (Yes/No)

income_annum: Annual income of the applicant

loan_amount: Amount of loan requested

loan_term: Term of the loan (in months)

cibil_score: Credit score of the applicant

residential_assets_value: Value of residential assets

commercial_assets_value: Value of commercial assets

luxury_assets_value: Value of luxury assets

bank_asset_value: Value of assets in bank accounts

loan_status: Status of the loan application (Approved/Rejected)

Code

loan_approval.ipynb: Jupyter notebook containing code for data exploration, preprocessing, and building a loan approval prediction model.
