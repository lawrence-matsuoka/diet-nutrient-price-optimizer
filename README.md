# diet-nutrient-price-optimizer

## Put all data into SQL database instead of just a .csv

- [When to use CSV vs Database](https://www.reddit.com/r/learnpython/comments/110mqci/when_to_use_csv_vs_database/)
- Nutrition table, macros table, high in carbs/protein/carbs table, prices have one column at the end
- atlantic-superstore-prices-and_nutrition-facts

## Scrape Atlantic Superstore grocery prices

- Scrape the only the grocery prices
- In theory could scrape the nutrition information and serving sizes directly from atlantic superstore too
- Will have to get the size of the item itself as well

## Scrape Cronometer nutrition data

- [Cronometer Scrape: GitHub project](https://github.com/bdero/cronometer-scrape)
- Must use CRDB since the most information will be there
- OR scrape from Atlantic Superstore directly as well

## Data cleaning

- If taking nutrition information and prices from different sources, will have to consolidate the differences in naming conventions or serving sizes

## Optimization with Julia and JuMP

- Code analysis and optimization with Julia and JuMP
- [The diet problem, JuMP documentation](https://jump.dev/JuMP.jl/stable/tutorials/linear/diet/)
- [Optimizing your diet with JuMP, blogpost](https://www.juliabloggers.com/optimizing-your-diet-with-jump-2/)

## Use Optimizer like GLPK or HiGHS or other Linear Programming software
