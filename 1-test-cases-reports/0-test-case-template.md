# Test Case Template

## Test Case Name: Financial Report Reconciliation (Balance Sheet)

### Objective:
To verify that the balance sheet data in OneStream matches SAP for the reporting period **01 Jan 2021 to 31 Dec 2021** across **5 APAC countries**.

### Test Steps:
1. Extract balance sheet data from SAP for the period **01 Jan 2021 to 31 Dec 2021**.
2. Extract balance sheet data from OneStream for the same period.
3. Compare key balance sheet items:
   - Assets
   - Liabilities
   - Equity
4. Identify any discrepancies greater than **$1,000**.
5. Document discrepancies in the [Issue Tracking Sheet](../Reports/Issue_Tracking_Template.md).
6. Present findings during the weekly UAT call.

### Expected Results:
- Data in OneStream should match SAP without discrepancies.
- Any differences should be less than **$1,000** and are expected to be resolved with country finance teams.

### Actual Results:
- [To be updated with test results for each country]

### Notes:
- For **Country A**, additional validation required due to local accounting standards.
