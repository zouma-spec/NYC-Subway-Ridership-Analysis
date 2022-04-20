# NYC Subway Ridership Analysis
## Abstract
The goal of this project is to investigate the current NYC subway ridership, especially in compare with pre-pandemic level, to determin its adversting value and to create a strategic pricing positoning for transit advertising. I worked with [MTA turnstile data](http://web.mta.info/developers/turnstile.html) for the time period of 2022 Q1(Jan, Feb and March). Besides the founding that 2022 Q1 traffic is 56.6% less than pre-pandemic level, it sees a 37.8% increase from 2021 Q1, which indicates a recovering sign from Covid.


## Design
My client is OUTFRONT Media, the company that handles all transit advertising opportunities of NYC subway except MetroCard®. 
My objective is to find the traffic volume distribution by location and time. First, find the distribution of subway ridership by stations and rank them in ridership shares. Based on that, find the ridership share for each day of week and each time period of day. 

 
## Data
The data I focus on is [MTA turnstile data](http://web.mta.info/developers/turnstile.html) for the time period of 2022 Q1(Jan, Feb and March). In order to compare the current traffic volume with previous times, I also used data from time period of 2019 Q1 and 2021 Q1.


## Algorithms
* Data loading and pre-investigate via SQL and SQLalchemy
* Data cleaning: rename weird column names, check and drop duplicate data
* Get daily entries of each turnstile
* Aggregate turnstile entries by stations and get station daily, monthly, quarterly total entries
* Focused on a one-week data of one station to get detailed time trend(day of week, time period of day)


## Tools

* SQL and SQLalchemy for preliminary data investigation
* Python Pandas for data manipulation
* Python Matplotlib and Seaborn for visualization

## Communication
Project deliverables are presented in slides which can be found in this repository.

