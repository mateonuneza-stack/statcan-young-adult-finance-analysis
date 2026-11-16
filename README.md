# statcan-young-adult-finance-analysis

## Project Objective
At the end of my Codecademy Python course, I was asked to pick my own dataset and analyze it. I wanted to use the project to explore a question I care about. After some thought, I wanted to look into: **How do the spending and balance sheets of young adults differ across life stages, and what products may they benefit from?**

## Datasets
*Naturally, I leaned toward Canadian data. Additionally, Statistics Canada had a large, organized site that was very easy to figure out how to use.*

- **household_spending.csv**: Household spending by age of reference person (Statistics Canada, 2023, Canada). Average expenditure per household across summary-level categories. Youngest band: less than 30. Comparison band: 30 to 39.
- **assets_and_debt.csv**: Assets, debts, and net worth by age group (Statistics Canada, 2023, Canada). Percent holding, median, and average values across asset and debt types. Youngest band: under 35. Comparison band: 35 to 44.


## Key Findings
- Spending: Compared with households led by someone aged 30–39, under-30 households spend a larger share on housing (26.2% vs. 24.1%) and transportation (12.7% vs. 10.9%). Food is slightly higher (11.2% vs. 10.6%), while insurance and pension contributions have negligible differences (6.7% vs. 7.1%).
- Assets: Family units led by someone under 35 have $245,200 in median total assets, compared with $645,000 for ages 35–44. These are asset values before subtracting debt.
- Debt: Debt is common in both groups: 78.3% of under-35 family units and 84.1% of those aged 35–44 hold some debt. Student loans are more common in the younger group (26.6% vs. 14.9%).
- Vehicle loans are similarly common among family units led by someone under 35 (35.3%) and those aged 35–44 (34.7%).
- Transportation takes a larger share of spending for under-30 households (12.7%) than for households aged 30–39 (10.9%). 

## Recommendation — product hypothesis
- **Debt-planning calculator**: Users could enter all their debts along with interest rates, see estimated payoff dates, and test how changing a monthly payment affects those dates and their other financial goals.
- **True Vehicle Cost Planner**: Based on my own experience, people severly underestimate the full cost of a car. A planner could show loan payments, fuel, insurance, and maintenance together to help users figure out if a vehicle truly fits their budget.


## Limitations
*I'd like to mention that I came up with my objective before looking at the datasets, which created limitations that could have been avoided. Nonetheless, I kept going because it would be a good learning opportunity.*

1. Age bands don't match. Statistics Canada publishes spending as under 30 and balance sheets as under 35. I use each as the closest available young-adult band. The under-35 group includes ages 30 to 34, so the wealth figures likely reflect a somewhat more established group than the spending figures. I therefore never mix the data.
2. Households, not individuals. Spending is per household and grouped by the age of the reference person. We therefore don't have information on young adults living at home.

## Conclusion
This project was a great learning experience, and I had a lot of fun working through the data. If I started again, I would check what data was available before settling on my questions. I wanted to understand young adults as individuals, but one dataset measures households and the other measures family units, with age groups that don’t quite match. That made the results harder to connect than I expected. I’m still satisfied with what I found about spending, assets, and debt, and the data gave me a starting point for a debt-planning product idea. I’d just treat that idea as a hypothesis to test, rather than something the numbers prove.
