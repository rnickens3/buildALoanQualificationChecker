# buildALoanQualificationChecker
JavaScript FreeCodeCamp.org tutorial completed August 5th, 2025

This JavaScript project includes a function that evaluates a person's **annual income** and **credit score** to determine their eligibility for different types of loans: **duplex**, **condo**, or **car**.

## Purpose

The `getLoanMessage()` function simplifies decision-making for loan eligibility by checking if a person meets the **minimum income** and **credit score** thresholds for each loan category.

## Loan Criteria

| Loan Type | Min Annual Income | Min Credit Score |
|-----------|-------------------|------------------|
| Duplex    | $60,000           | 700              |
| Condo     | $45,000           | 680              |
| Car       | $30,000           | 650              |

## Function Usage

```javascript
getLoanMessage(annualIncome, creditScore);
