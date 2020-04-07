# Analysis of COVID-19 Data from The New York Times

*Author: Mark Bauer*  
*Date Created: March 28, 2020*  
*Date Updated: April 6, 2020*

The New York Times Github Data Repository: https://github.com/nytimes/covid-19-data.   
The New York Times News Article: https://www.nytimes.com/article/coronavirus-county-data-us.html.  
The New York Times COVID-19 US Map: https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html.   
The New York Times COVID-19 Global Map: https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html.  


 

# Tables

**Table 1. Coronavirus (COVID-19) Cases in the United States (Top 10 States)**

|    | date       | state         | cases   | deaths   |
|---:|:-----------|:--------------|--------:|---------:|
|  0 | 2020-04-05 | New York      | 122,911 | 4,161    |
|  1 | 2020-04-05 | New Jersey    | 37,505  | 917      |
|  2 | 2020-04-05 | Michigan      | 15,635  | 616      |
|  3 | 2020-04-05 | California    | 15,076  | 349      |
|  4 | 2020-04-05 | Louisiana     | 13,010  | 477      |
|  5 | 2020-04-05 | Massachusetts | 12,500  | 231      |
|  6 | 2020-04-05 | Florida       | 12,342  | 220      |
|  7 | 2020-04-05 | Pennsylvania  | 11,589  | 159      |
|  8 | 2020-04-05 | Illinois      | 11,276  | 282      |
|  9 | 2020-04-05 | Washington    | 7,984   | 344      |  


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

![numer of cases state choropleth map ](figures/nyt-covid-19-data-state-map-choro.png)


## Tree Maps

![numer of cases state treemap](figures/nyt-covid-19-data-treemap.png)
