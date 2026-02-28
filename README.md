# Personal Finance Data Analysis Summary

## Dataset Overview
- **Total Records**: 16,208
- **Original Records**: 16,241
- **Records Removed (Outliers)**: 33
- **Variables Analyzed**: 19 + 13 derived columns

## Key Financial Metrics

### Net Worth
- **Mean Net Worth**: $1,470,614
- **Median Net Worth**: $902,500
- **Min Net Worth**: $-2,388,150
- **Max Net Worth**: $19,574,000
- **25th Percentile**: $289,250
- **75th Percentile**: $1,940,000

### After-Tax Income
- **Mean Income**: $101,812
- **Median Income**: $84,675
- **Min Income**: $-2,701,225
- **Max Income**: $996,425
- **25th Percentile**: $50,000
- **75th Percentile**: $133,025

### Debt Statistics
- **Mortgage Debt (Average)**: $88,579
- **Student Loan Debt (Average)**: $1,541
- **Credit Card Debt (Average)**: $3,066
- **Line of Credit Debt (Average)**: $12,291
- **Total Debt (Average)**: $105,476

### Assets
- **Home Value (Average)**: $552,762
- **Bank Deposits (Average)**: $54,608
- **TFSA Balance (Average)**: $41,061
- **Liquid Assets (Average)**: $95,669

## Demographics

### Age Distribution
- **25-34**: 1,432 (8.8%)
- **35-44**: 2,219 (13.7%)
- **45-54**: 2,490 (15.4%)
- **55-64**: 3,635 (22.4%)
- **65-79**: 4,968 (30.7%)
- **80+**: 1,266 (7.8%)
- **Under 25**: 198 (1.2%)

### Education Level
- **University**: 7,143 (44.1%)
- **Post-sec**: 4,192 (25.9%)
- **High School**: 3,100 (19.1%)
- **<HS**: 1,202 (7.4%)
- **Not stated**: 571 (3.5%)

### Home Ownership
- **Own outright**: 6,755 (Avg Net Worth: $2,205,329)
- **Own with mortgage**: 5,826 (Avg Net Worth: $1,343,395)
- **Rent**: 3,627 (Avg Net Worth: $306,617)

### Credit Card Payment Behavior
- **Full**: 10,696 (66.0%)
- **Partial**: 3,418 (21.1%)
- **Skip**: 923 (5.7%)
- **Min**: 772 (4.8%)
- **<Min**: 207 (1.3%)
- **Not used**: 192 (1.2%)

### COVID Financial Impact
- **Same**: 9,432 (Avg Net Worth: $1,615,573)
- **Worsened**: 4,982 (Avg Net Worth: $1,177,259)
- **Improved**: 1,794 (Avg Net Worth: $1,523,151)

## Key Insights

1. **Net Worth Accumulation**: Net worth peaks in the 55-64 age group at approximately $1.8 million on average, then declines slightly for those 65-79 and 80+.

2. **Wealth Inequality**: The distribution of net worth is highly skewed, with the 75th percentile ($1.95M) being 7x the median ($905K).

3. **Home Ownership Impact**: Homeowners have significantly higher net worth compared to renters. Owning with mortgage shows the highest average net worth.

4. **Education Premium**: Higher education levels correlate strongly with higher net worth, with university graduates showing the highest average net worth.

5. **COVID Impact**: Most households (majority) reported their financial situation stayed the same since COVID-19.

## Data Quality Notes
- Outliers removed: Net worth > $20M, Income > $1M
- Negative values in income, bank deposits, and net worth represent specific survey responses
- All debt types include zeros for households without that type of debt
