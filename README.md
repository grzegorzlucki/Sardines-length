# Sardines Length Distribution Test

This analysis focuses on determining whether the distribution of sardines' length follows a normal distribution or not.

## Data
The data used for this analysis is stored in the `sardines.csv` file and consists of three columns: `from`, `to`, and `quantity`, representing the length intervals and the corresponding quantities of sardines.

### Data Preview
| from | to  | quantity |
|------|-----|----------|
| 10   | 12  | 10       |
| 12   | 14  | 26       |
| 14   | 16  | 56       |
| 16   | 18  | 64       |
| 18   | 20  | 30       |
| 20   | 22  | 14       |

## Analysis Steps

### 1) Data Preparation:
- Loaded the data from the `sardines.csv` file.
- Calculated average and standard deviation of sardines' length distribution.

### 2) Data Visualization:
- Created a bar chart to visualize the quantity of sardines in different length intervals.

### 3) Statistical Analysis:
- Utilized the chi-square goodness-of-fit test to assess whether the length distribution is normal.
- Determined the chi-square statistic, level of significance, number of degrees of freedom, and critical chi-square value.
- Compared the chi-square statistic with the critical chi-square value to make a decision.

## Results and Conclusion

### Chi-Square Test Results
- **Chi-Square Statistic:** 1.3716
- **Level of Significance:** 0.1
- **Number of Degrees of Freedom:** 3
- **Critical Chi-Square Value (Q):** (6.2514, +∞)

### Conclusion
Since the calculated chi-square statistic (1.3716) is not in the critical region (Q < 1.3716), we do not have enough evidence to reject the null hypothesis (H0) that the distribution of sardines' length is normal. Therefore, based on this test, it can be concluded that the sardines' length follows a normal distribution.
