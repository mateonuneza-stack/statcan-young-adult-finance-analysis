# statcan-young-adult-finance-analysis

## Project Objective
At the end of my Codecademy Python course, I was asked to pick my own dataset and analyze it. I wanted to use the project to explore a question I care about. After some thought, I wanted to ask: **How do the spending and balance sheets of young adults differ across life stages?**

## Datasets
*Naturally, I leaned toward Canadian data. Additionally, Statistics Canada had a large, organized site that was very easy to figure out how to use.*

- **household_spending_2023.csv**: Household spending by age of reference person (Statistics Canada, 2023, Canada). Average expenditure per household across summary-level categories. Youngest band: less than 30. Comparison band: 30 to 39.
- **assets_and_debt_2023.csv**: Assets, debts, and net worth by age group (Statistics Canada, 2023, Canada). Percent holding, median, and average values across asset and debt types. Youngest band: under 35. Comparison band: 35 to 44.

## Method
- Filtered both tables to 2023 and Canada on the Statistics Canada website before downloading them.
- Kept the two age groups for each comparison, renamed the spending columns, and selected the balance-sheet columns and statistics needed for the analysis.
- Combined the food and transportation categories, then divided each spending category by total household expenditure to calculate its budget share.
- Used pivot tables to compare spending shares, percentage holding, and median values by age group. The spending and balance-sheet age bands were kept separate.
- Computed each age group's aggregate debt-to-asset ratio as total debt divided by total assets.

## Key Findings
- Spending: Spending shares differ only slightly. Under-30 households spend slightly more of their budget on housing (26.2% vs 24.1%), transportation (12.7% vs 10.9%) and food (11.2% vs 10.6%) than households aged 30 to 39.
- Assets: Family units led by someone under 35 have $245,200 in median total assets, compared with $645,000 for ages 35–44. These are asset values before subtracting debt.
- Debt: Based on total values, debt relative to assets is nearly identical across the two groups. The debt-to-asset ratio is 24.1% for under-35 family units and 24.3% for ages 35 to 44. The data shows no meaningful difference here. These figures divide aggregate total debt by aggregate total assets; they do not describe the ratio for a typical household.
- Vehicle loans are similarly common among family units led by someone under 35 (35.3%) and those aged 35–44 (34.7%).

## Further Questions
- Debt is common in both groups. What types of debt do individuals carry? Answering this would require individual-level data and further analysis.
- Do these patterns hold beyond 2023? How do spending, assets, and debt compare before and after COVID-19, and what might explain any differences? Answering this would require data from multiple years and, ideally, individual-level data rather than figures grouped by household or family unit.

## Limitations
*I'd like to mention that I came up with my objective before looking at the datasets, which created limitations that could have been avoided. Nonetheless, I kept going because it would be a good learning opportunity.*

1. Age bands don't match. Statistics Canada publishes spending as under 30 and balance sheets as under 35. I use each as the closest available young-adult band. The under-35 group includes ages 30 to 34, so the wealth figures likely reflect a somewhat more established group than the spending figures. I therefore never mix the data.
2. Households, not individuals. Spending is per household and grouped by the age of the reference person. We therefore don't have information on young adults living at home.

## Conclusion
This project was a great learning experience, and I had a lot of fun working through the data. If I started again, I would check what data was available before settling on my questions. I wanted to understand young adults as individuals, but one dataset measures households and the other measures family units, with age groups that don’t quite match. That made the results harder to connect than I expected. I’m still satisfied with what I found about spending, assets, and debt, and the data gave me a clearer question to investigate next.
