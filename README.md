# Analysis of COVID-19 Data from The New York Times

*Author: Mark Bauer*  
*Date Created: March 28, 2020*  
*Date Updated: April 17, 2020*

The New York Times Github Data Repository: https://github.com/nytimes/covid-19-data.   
The New York Times News Article: https://www.nytimes.com/article/coronavirus-county-data-us.html.  
The New York Times COVID-19 US Map: https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html.   
The New York Times COVID-19 Global Map: https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html.  


 

# Tables

**Table 1. Coronavirus (COVID-19) Cases in the United States (Top 10 States)**

|    | date       | state         | cases   | deaths   |
|---:|:-----------|:--------------|--------:|---------:|
|  0 | 2020-04-16 | New York      | 222,284 | 12,192   |
|  1 | 2020-04-16 | New Jersey    | 75,317  | 3,518    |
|  2 | 2020-04-16 | Massachusetts | 32,181  | 1,245    |
|  3 | 2020-04-16 | Michigan      | 29,119  | 2,091    |
|  4 | 2020-04-16 | Pennsylvania  | 28,314  | 864      |
|  5 | 2020-04-16 | California    | 28,142  | 971      |
|  6 | 2020-04-16 | Illinois      | 25,734  | 1,081    |
|  7 | 2020-04-16 | Florida       | 23,332  | 667      |
|  8 | 2020-04-16 | Louisiana     | 22,532  | 1,156    |
|  9 | 2020-04-16 | Texas         | 16,927  | 431      |  


# Bar Charts

![numer of cases state horizontal](figures/nyt-covid-19-data-barh.png) 

![epi curve](figures/epi_curve.png)   

# Figures

##  Number of Positives Per Day

### Weekly Average

![days since 10 daily cases top 10 weekly](figures/10-cases-timeseries-by-state-top-10-weekly.png)

![days since 10 daily cases top 10 weekly log](figures/10-cases-timeseries-by-state-top-10-weekly-log.png) 

### Daily

![days since 10 daily cases top 10 daily](figures/10-cases-timeseries-by-state-top-10-daily.png)

![days since 10 daily cases top 10 daily log](figures/10-cases-timeseries-by-state-top-10-daily-log.png)


##  Growth Factor of Number of Positives per Day

### Weekly Average

![growth factor daily cases top 10 weekly](figures/growth-factor-top-10-weekly.png)

### Daily 

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

![number of cases trajectory states weekly average 900 case min](figures/nyt-covid-19-all-states-trajectory-weekly-plot-labels-xlimit.png)

![number of cases trajectory states weekly average](figures/nyt-covid-19-all-states-trajectory-weekly-plot-labels.png) 

![number of cases trajectory usa weekly average](figures/nyt-covid-19-usa-trajectory-weekly-plot.png)


## Time Series

### Top 10 States
![number of cases timeseries](figures/nyt-covid-19-state-timeseries.png)

![number of cases timeseries log](figures/nyt-covid-19-state-timeseries-log.png)

### United States
![number of cases linear](figures/nyt-covid-19-data-linear.png)

![number of cases log](figures/nyt-covid-19-data-log.png)  


## Maps

![numer of cases state map](figures/nyt-covid-19-data-state-map.png)

