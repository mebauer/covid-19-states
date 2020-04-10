# Analysis of COVID-19 Data from The New York Times

*Author: Mark Bauer*  
*Date Created: March 28, 2020*  
*Date Updated: April 9, 2020*

The New York Times Github Data Repository: https://github.com/nytimes/covid-19-data.   
The New York Times News Article: https://www.nytimes.com/article/coronavirus-county-data-us.html.  
The New York Times COVID-19 US Map: https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html.   
The New York Times COVID-19 Global Map: https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html.  


 

# Tables

**Table 1. Coronavirus (COVID-19) Cases in the United States (Top 10 States)**

|    | date       | state         | cases   | deaths   |
|---:|:-----------|:--------------|--------:|---------:|
|  0 | 2020-04-08 | New York      | 149,401 | 6,268    |
|  1 | 2020-04-08 | New Jersey    | 47,437  | 1,504    |
|  2 | 2020-04-08 | Michigan      | 20,220  | 959      |
|  3 | 2020-04-08 | California    | 19,043  | 506      |
|  4 | 2020-04-08 | Louisiana     | 17,030  | 652      |
|  5 | 2020-04-08 | Massachusetts | 16,790  | 433      |
|  6 | 2020-04-08 | Pennsylvania  | 16,414  | 313      |
|  7 | 2020-04-08 | Florida       | 15,690  | 322      |
|  8 | 2020-04-08 | Illinois      | 15,078  | 464      |
|  9 | 2020-04-08 | Georgia       | 10,204  | 370      |  


## Bar Charts

![numer of cases state horizontal](figures/nyt-covid-19-data-barh.png)  

# Figures

##  Number of Positives Per Day

![days since 10 daily cases top 10 weekly](figures/10-cases-timeseries-by-state-top-10-weekly.png)

![days since 10 daily cases top 10 weekly log](figures/10-cases-timeseries-by-state-top-10-weekly-log.png) 


##  Growth Factor of Number of Positives per Day

![growth factor daily cases top 10 weekly](figures/growth-factor-top-10-weekly.png)

![growth factor daily cases top 10 daily](figures/growth-factor-top-10-daily.png)


## Cumulative Number of Positive Cases  

### Top 10 States
![number of cases timeseries tenth case](figures/nyt-covid-19-state-timeseries-tenth-case.png)

![number of cases timeseries tenth case log](figures/nyt-covid-19-state-timeseries-tenth-case-log.png)  

### All States
![days since 10 cases](figures/10-cases-timeseries-by-state.png)

![days since 10 cases log](figures/10-cases-timeseries-by-state-log.png)


## Trajectory of Number of Positive Cases

![number of cases trajectory weekly average](figures/nyt-covid-19-state-trajectory-weekly-plot.png)   

![number of cases trajectory states weekly average](figures/nyt-covid-19-all-states-trajectory-weekly-plot-labels.png) 

![number of cases trajectory usa weekly average](figures/nyt-covid-19-usa-trajectory-weekly-plot.png)


## Time Series

### Top 10 States
![number of cases timeseries](figures/nyt-covid-19-state-timeseries.png)

![number of cases timeseries log](figures/nyt-covid-19-state-timeseries-log.png)

### As a Country
![number of cases linear](figures/nyt-covid-19-data-linear.png)

![number of cases log](figures/nyt-covid-19-data-log.png)  


## Maps

![numer of cases state map](figures/nyt-covid-19-data-state-map.png)


## Tree Maps

![numer of cases state treemap](figures/nyt-covid-19-data-treemap.png)
