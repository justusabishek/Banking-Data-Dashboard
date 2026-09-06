# Banking Data Dashboard

## Problem Statement:

This dashboard helps banks understand customer behavior, account activity, and transaction trends. It highlights inactive accounts, monthly transaction volumes, and balances across account types. By analyzing these metrics, banks can identify areas of concern such as declining balances, inactive accounts, or irregular transaction patterns, and take corrective measures to improve customer engagement and financial performance.

For example, the dashboard shows fluctuations in monthly transaction amounts and a significant negative balance in current accounts, which signals the need for better monitoring and customer support. It also provides demographic insights such as customer count by gender, helping banks tailor services more effectively.

### Steps Followed:

- Step 1: Data was loaded into Power BI from Microsoft SQL Server(The Data is created using AI Tools).

- Step 2: Data cleaning and transformation were performed using Power Query.

- Step 3: Null values and blanks were handled, especially in customer demographic fields.

- Step 4: Visuals were created to represent transaction amounts, inactive accounts, balances, and customer counts.

- Step 5: Slicers and filters were added to allow drill-down by account type, transaction type (credit/debit), and time period.

- Step 6: Card visuals were used to display KPIs such as total transactions and balances.

- Step 7: Line and bar charts were used to show monthly transaction trends and inactive accounts over time.

- Step 8: The report was published to Power BI Service for sharing and collaboration.

### Snapshot of Dashboard (Power BI Service)
![snap](https://github.com/justusabishek/Power-BI-Project-Using-AI/issues/1#issue-5366433983)

## Insights: 

A single-page report was created on Power BI Desktop and published to Power BI Service. Key inferences include:

### [1] Customer Demographics:

Customer count is segmented by gender, with representation across male, female, and blank categories.

### [2] Account Activity:

Inactive accounts are tracked monthly, showing peaks in certain months (e.g., May, July, November 2025).

This helps identify periods of reduced engagement.

### [3] Transaction Trends:

Monthly transaction amounts vary significantly, with peaks in April (4.0M) and December (4.0M), and lows in May (0.8M).

Such fluctuations indicate seasonal or campaign-driven customer activity.

### [4] Account Balances:

Savings accounts show stable balances, while current accounts reflect a large negative balance (-15.8M).

This highlights potential overdraft or operational issues requiring immediate attention.

### [5] Transaction Types:

Credit and debit transactions are balanced, with approximately 5K transactions each.

### Conclusion:

This Bank Dashboard provides actionable insights into customer demographics, account activity, and transaction trends. By monitoring inactive accounts, monthly transaction volumes, and account balances, banks can improve customer satisfaction, reduce risks, and optimize financial performance.
