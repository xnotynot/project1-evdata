# Examining factors associated with Electric Vehicle (EV) adoption
___________________________________________________________________________________
With the popularity of EVs, it is a relevant topic and highly applicable. For our group project, we explored the factors associated with EV sales and adoption. We explored the following questions:
* Is there correlation between income and EV adoption?
* What makes and models of EV are most popular?
* Which EV car model is most cost and energy efficient?
* What is the relationship between EV sales per state and that state’s median income?
* What is the relationship between EV car sales and available charging infrastructure across US states?
* What is the relationship between EV infrastructure and total population across US states?
___________________________________________________________________________________
## Overview
Electric vehicles are either partially or fully powered by electric power. They are broadly classified into three types:
- All-electric vehicles – These vehicles have a battery that is charged through an electric plug-in. A single charge can yield driving ranges from 150-400 miles.
- Plug-In Hybrid EV- These EVs operate on a combination of charged battery and gasoline with 15-60 miles solely on a charged battery.
- Hybrid EV- HEVs are not electric at all. These depend primarily on gasoline, and the battery is charged through regenerative braking.

For the purpose of our project we are considering only "All electric Vehicles"
___________________________________________________________________________________
## Factors
EV sales are surging due to a combination of multiple factors:
- High fuel prices
- Emphasis on climate mitigation initiatives
- Availability of charging infrastructure
- Governmental policies support
- Improvements in car and battery technology 

All these have prompted an increase in EV sales and adoption. The sale cost of EVs is higher than a traditional car and can be prohibitive in EV adoption.
___________________________________________________________________________________
### Data
* Sources - US census Bureau https://www.census.gov/topics/population/data.html
* Alternate Fules Data Center - US Department of Energy https://afdc.energy.gov/
* Median income data was provided by: https://worldpopulationreview.com/state-rankings/median-household-income-by-state
* Electric Vehicle data: https://www.surfky.com/electric-car-sales-by-state (This data was amassed using numbers provided by the U.S. Department         of Transportation (USDT) and the California Energy Commission (CEC), among others).
* Metric data for each car was provided by: https://www.kaggle.com/code/tyrawls/electric-vehicle-analysis/report 
___________________________________________________________________________________
### EV Sales - Top 10 EV Models - 2015 to 2019
Tesla Model 3 was the most popular EV vehicle. Even though Tesla Model 3 was launched in 2017, it represents 39% of the top ten EV car sales from 2015-2019. All the Tesla models together (model 3,S,X) represents 59% of EV car sales.

![Total EV Sales Top 10 EV Models 2015 to 2019](https://github.com/xnotynot/project1-evdata/blob/acc48d2cc40a9329e0725f310d200ddabf6daae2/Graphs/toptenSales.PNG)
___________________________________________________________________________________
### Technical Analysis of EVs
* Analyzed technical data for a large amount of EVs in the market. 
* We sought to answer two primary questions: 
	* Which vehicles have the best efficiency in Watt Hours/Kilometer
	* Which has the best cost efficiency in Price of Vehicle/Miles.

### Best Efficieny in Watt Hours Per Kilometer
* Information pertaining to 102 electric vehicles was attained and the top 10 most efficient vehicles were listed and then graphed. 
* The top 3 most efficient cars were the Lightyear One, Hyundai IONIQ Electric and Tesla Model 3 Standard Range Plus with WH/Km values of 104, 153, 153. 
* Conclusion: The clear winner in our metric for efficiency is the Lightyear One, so consumers who are looking for a vehicle that gets the most distance per charge may want to purchase this one. As an aside, currently this vehicle is only available in select European markets and is not sold in the United States.

![Most Efficient Cars by WHKm](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Most%20Efficient%20EVs%20(WHKm).png)
_______________________________________________________________________________
### Cost Efficiency in Price of Vehicle Per Mile
* For cost efficiency analysis we computed the price per mile when on a full charge of its battery. 
* This metric helps to measure how much customers pay for each mile (this data does not take into account the cost of charge for each vehicle). 
* According to our metric the most cost efficient cars were:
	1. Volkswagen ID.3 Pro - Price to mile ratios of $149.73
	2. Volkswagen ID.3 Pro S - Price to mile ratios of $151.74
	3. Skoda Enyaq iV 80 with - Price to mile ratios of $153.27
* From this data it seems that Volkswagen makes the most Price efficient cars for its customers.

![Most Cost Efficient Cars](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Cost%20Efficiency%20(PriceMile).png)
___________________________________________________________________________________
### Median Income Vs Electric Vehicles Registered (By State) - 2016 to 2020
* r-value between these two variables was 0.26, which shows little to no correlation between the median income and EV purchases of each state.
* This seems to highlight the fact there are other variables as to why and where EVs are purchased. 
* These range from government financial incentives/subsidies, political/demographic populations of each state, availability to charging stations and many more. 

![State Median Income vs Evs Registered by State](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Registered%20EVs%20vs%20State%20Median%20Income%20(including%20California).png)

### Median Income Vs Electric Vehicles Registered (By State - Exclulding California)
* The one obvious takeaway from the first graph was that California was an outlier in how many EVs were registered when compared to its median state income. 
* Over the five year span California registered 617,830 electric vehicles whereas the second place state (New York) only added 62,237 vehicles in the same time span.
* To account for this outlier a new graph was created excluding California
* This new graph returned an r-value of 0.40 which shows a moderate correlation between the two variables.
* Although still being a low value this higher correlation shows that a states median income moderately accounts for EV purchases by state. 

![State Median Income vs Evs Registered by State (Excluding California)](https://github.com/xnotynot/project1-evdata/blob/main/Graphs/Registered%20EVs%20vs%20State%20Median%20Income%20(excluding%20California).png)
_______________________________________________________________________________
### EV Sales Vs Charging Infrastructure
- It is observed that increase in charging infrastructure has a direct impact on the sales, case in point california where the sales dropped in 2019 with drop in charging infra
- Oregon on the other hand continued to grow until 2020 where there is a drop in both charging infra and sales
![EV Sales Vs Charging Infrastructure](https://github.com/xnotynot/project1-evdata/blob/22677d964a78037c7f7c5197583eb9c430641d39/Graphs/SlsVsChargInfra.png)

### EV Sales Vs Total Population
![EV Sales Vs Total Population](https://github.com/xnotynot/project1-evdata/blob/6298671f69e73f73c94f74301114adb5a4d9e525/Graphs/SalesVsTotalPopulation.png)

### Per Capita EV Charge Stations
There are states where the charging infrastructure stagnated after a certain number of installations. Case in point, Alaska. There could be various factors like per capita charging station might be higher 
![Per Capita Charge Station](https://github.com/xnotynot/project1-evdata/blob/6298671f69e73f73c94f74301114adb5a4d9e525/Graphs/PerCapitaChargeInfra.png)

_______________________________________________________________________________
# Conclusions
* Tesla 59% of total EV sales 2015-2019
* Tesla Model 3 came on top as the top seller and one of the most efficient cars
* Recent data suggests that the most efficient energy EV is Tesla Model 3 and Volkswagen ID3 is most cost-effective EV
* There is a trend that suggests EV adoption is related to income.
* Positive and high association between EV sales and charging infrastructure (r=0.96-97) from 2016-2020
* ↑ in charging infrastructure has a direct impact on the EV sales
* In some states observed saturation point in charging infrastructure
