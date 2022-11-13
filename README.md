# project1-evdata

## EV Adoption 

### Objective:
Determine the factors that influence the growth of EV adoption
EV car sales

## Compare median income in a state with EV adoption
	- Correlation between income and EV adoption
	- Observation - Is there a relationship between the median income and EV adoption
	- Datasources required - Median income for state(s) BLS and EV adoption by state(s)
	- Which states have the highest EV adoption rate
	
## Accessibility to Charging Infrastructure 
	- Correlation between growth in charging infrastructure and EV adoption
	- Datasource required - EV charging stations by location(city/state) and EV cars (city/state)
	
___________________________________________________________________________________
EV Sales Vs Charging Infrastructure
![EV Sales Vs Charging Infrastructure](https://github.com/xnotynot/project1-evdata/blob/22677d964a78037c7f7c5197583eb9c430641d39/Graphs/SlsVsChargInfra.png)

Question 1: Is there a relation between a states median income (United States) and the amount of Electric Vehicles purchased/registered in that state?

In this section of our project we sought to answer the question: Is there a relationship between the median state income (for the United States) and the number of EV cars registered in that respective state between the years of 2016-2020? When graphed, we found that the R-value between these two variables was 0.26, which shows little to no correlation between the median income and EV purchases of each state. Although this lack of correlation is surprising it seems to highlight the fact that many different variables play into why and where EVs are purchased. These range from government financial incentives/subsidies, political/demographic populations of each state, availability to charging stations and many more. 

State Median Income vs Evs Registered by State
![State Median Income vs Evs Registered by State](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/EV_count%20vs%20Median_income.PNG)


The one obvious takeaway from the first graph was that California was an outlier in how many EVs were registered when compared to its median state income. Over the five year span California registered 617,830 electric vehicles whereas the second place state (New York) only added 62,237 vehicles in the same time span. To account for this outlier a new graph was created that contained the same information as the first, except this time California was removed from the data set. This new graph returned an R-value of 0.40 which shows a moderate correlation between the two variables. Although still being a low value this higher correlation shows that a states median income moderately accounts for EV purchases by state. 

Median income data was provided by: https://worldpopulationreview.com/state-rankings/median-household-income-by-state

Electric Vehicle data was provided by: https://www.surfky.com/electric-car-sales-by-state (This data was amassed using numbers provided by the U.S. Department of Transportation (USDT) and the California Energy Commission (CEC), among others).
