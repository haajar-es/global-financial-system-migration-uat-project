# Test Case: Profit & Loss Report Validation

## Objective:
Ensure that the P&L report for **December 2021** in **OneStream** matches the financial data in **SAP** across 5 APAC countries.

### Test Steps:
1. Extract P&L data from SAP for the period **01 December 2021 - 31 December 2021**.
2. Extract P&L data from OneStream for the same period.
3. Compare revenue, cost of sales, and gross margin.
4. Validate key expense categories:
   - Selling Expenses
   - General and Administrative Expenses
   - Other Operating Expenses
5. Highlight any discrepancies over **$5,000**.

### Expected Results:
- Total revenue, expenses, and gross profit should match between systems with no discrepancies.

### Actual Results:
- Discrepancies found for **Country B** in selling expenses. To be resolved with the finance team.

### Resolution:
- Adjusted mapping for selling expenses in OneStream, bringing discrepancies down to **$500**.


