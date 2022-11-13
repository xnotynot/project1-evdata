# Examining factors associated with Electric Vehicle (EV) adoption
___________________________________________________________________________________
With the popularity of EVs, it is a relevant topic and highly applicable. For our group project, we explored the factors associated with EV sales and adoption. We explored the following questions
* Correlation between income and EV adoption
* What makes and models of EV are most popular?
* Which EV car model is most cost and energy efficient?
* What is the relationship between EV sales per state and that state’s median income?
* What is the relationship between EV car sales and available charging infrastructure across US states?
___________________________________________________________________________________
## Overview
Electric vehicles are either partially or fully powered by electric power. They are broadly classified into three types.
- All-electric vehicles – These vehicles have a battery that is charged through an electric plug-in. A single charge can yield driving ranges from 150-400 miles.
- Plug-In Hybrid EV- These EVs operate on a combination of charged battery and gasoline with 15-60 miles solely on a charged battery.
- Hybrid EV- HEVs are not electric at all. These depend primarily on gasoline, and the battery is charged through regenerative braking.
___________________________________________________________________________________
## Factors
EV sales are surging due to a combination of multiple factors. Not in a specific order:
- High fuel prices
- Emphasis on climate mitigation initiatives
- Availability of charging infrastructure
- Governmental policies support
- Improvements in car and battery technology 

All these have prompted an increase in EV sales and adoption. The sale cost of EVs is higher than a traditional car and can be prohibitive in EV adoption.
___________________________________________________________________________________
### Data
	- Sources - US census Bureau https://www.census.gov/topics/population/data.html
	- Alternate Fules Data Center - US Department of Energy https://afdc.energy.gov/
	-Median income data was provided by: https://worldpopulationreview.com/state-rankings/median-household-income-by-state
	-Electric Vehicle data was provided by: https://www.surfky.com/electric-car-sales-by-state (This data was amassed using numbers provided by the U.S. Department         of Transportation (USDT) and the California Energy Commission (CEC), among others).
	-Metric data for each car was provided by: https://www.kaggle.com/code/tyrawls/electric-vehicle-analysis/report 
___________________________________________________________________________________
### EV Sales Vs Charging Infrastructure
### Study of Relationship between EV Sales and EV charging infrastructure
* This notebook contains the analysis of relationship between EV sales and EV charging infrastructure
* Sales Vs Overall Population
* 
### Correlation of EV Sales and Charging Infrastructure
- Observation - Charging infrastructure has a direct correlation with sales of EV
![EV Sales Vs Charging Infra Correlation](https://github.com/xnotynot/project1-evdata/blob/03d3ed3d455eb70c7a4f81d189830eeb517ad2a0/Graphs/SlsVsChargInfraCorrelation.png)

### EV Sales Vs Charging Infrastructure
- It is observed that increase in charging infrastructure has a direct impact on the sales, case in point california where the sales dropped in 2019 with drop in charging infra
- Oregon on the other hand continued to grow until 2020 where there is a drop in both charging infra and sales
![EV Sales Vs Charging Infrastructure](https://github.com/xnotynot/project1-evdata/blob/22677d964a78037c7f7c5197583eb9c430641d39/Graphs/SlsVsChargInfra.png)

### EV Sales Vs Total Population
![EV Sales Vs Total Population](https://github.com/xnotynot/project1-evdata/blob/6298671f69e73f73c94f74301114adb5a4d9e525/Graphs/SalesVsTotalPopulation.png)

### Per Capita EV Charge Stations
There are states where the charging infrastructure stagnated after a certain number of installations. Case in point, Alaska. There could be various factors like per capita charging station might be higher 
![Per Capita Charge Station](https://github.com/xnotynot/project1-evdata/blob/6298671f69e73f73c94f74301114adb5a4d9e525/Graphs/PerCapitaChargeInfra.png)

___________________________________________________________________________________

### Relation between states median income (United States) and the amount of Electric Vehicles purchased/registered in that state

In this section of our project we sought to answer the question: Is there a relationship between the median state income (for the United States) and the number of EV cars registered in that respective state between the years of 2016-2020? When graphed, we found that the R-value between these two variables was 0.26, which shows little to no correlation between the median income and EV purchases of each state. Although this lack of correlation is surprising it seems to highlight the fact that many different variables play into why and where EVs are purchased. These range from government financial incentives/subsidies, political/demographic populations of each state, availability to charging stations and many more. 

![State Median Income vs Evs Registered by State](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Registered%20EVs%20vs%20State%20Median%20Income%20(including%20California).png)

The one obvious takeaway from the first graph was that California was an outlier in how many EVs were registered when compared to its median state income. Over the five year span California registered 617,830 electric vehicles whereas the second place state (New York) only added 62,237 vehicles in the same time span. To account for this outlier a new graph was created that contained the same information as the first, except this time California was removed from the data set. This new graph returned an R-value of 0.40 which shows a moderate correlation between the two variables. Although still being a low value this higher correlation shows that a states median income moderately accounts for EV purchases by state. 

![State Median Income vs Evs Registered by State (Excluding California)](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Registered%20EVs%20vs%20State%20Median%20Income%20(excluding%20California).png)
_______________________________________________________________________________

### Technical Analysis of EVs

For this portion of the project we took a look at some of the technical data for a large amount of EVs in the market. We sought to answer two primary questions: which vehicles have the best efficiency in Watt Hours/Kilometer and which has the best cost efficiency in Price of Vehicle/Miles. For our first question, information pertaining to 102 electric vehicles was attained and the top 10 most efficient vehicles were listed and then graphed. The top 3 most efficient cars were the Lightyear One, Hyundai IONIQ Electric and Tesla Model 3 Standard Range Plus with WH/Km values of 104, 153, 153. The clear winner in our metric for efficiency is the Lightyear One, so consumers who are looking for a vehicle that gets the most distance per charge may want to purchase this one. As an aside, currently this vehicle is only available in select European markets and is not sold in the United States.

![Most Efficient Cars by WHKm](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Most%20Efficient%20EVs%20(WHKm).png)

For cost efficiency analysis we took the base price of each EV and divided by the max range the EV could travel when on a full charge of its battery. This metric helps to measure how much money you are paying for each mile you are able to travel with each EV (this data does not take into account the cost of charge for each vehicle). According to our metric the most cost efficient cars were the Volkswagen ID.3 Pro, Volkswagen ID.3 Pro S and the Skoda Enyaq iV 80 with Price to mile ratios of $149.73, $151.74 and $153.27. From this data it seems that Volkswagen makes the most Price efficient cars for its customers.

![Most Cost Efficient Cars](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Cost%20Efficiency%20(PriceMile).png)



