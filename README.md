# INDIVIDUAL PROJECT DATA ANALYST
## Air Accidents 1908 - 2021
### Amelia Herrera Briceño
melinnicri@gmail.com


<p align="center"><img src="https://github.com/melinnicri/Air_accidents/blob/main/images/plane.png"></p>



## Background:
<center>
Airplane accidents are tragic events that can have serious consequences.
Although plane accidents are less common than car accidents, they are usually more serious due to the speed and height involved.
Plane crashes can also have a higher number of victims due to the large number of people that can be on a single plane (900 maximum).
</center>

## Considerations:
<center>
According to the International Civil Aviation Organization (ICAO), the number of global air accidents has been decreasing over the years. In 2019, there were 13 accidents, which is a decrease from 2018, when there were 18 accidents.
One dataset provides a complete history of air crashes worldwide from 1908 to 2021. It contains information on more than 4,000 air crashes, including location, operator, and fatalities (passengers and crew).
In terms of deaths, they have been recorded in air travel in each of the last 16 years, with a total of 128 deaths in 2021 due to air accidents.
According to the data analysis see [PowerBI Dashboard](https://github.com/melinnicri/Air_accidents/blob/main/Air_traficc.pbix), there has been a downward trend since 2004; 
- KPI1: regarding the 10% reduction in crew fatality between 2001 and 2021, for the range 2001-2011, it is decreased by (-0.30). For the 2011-2021 range, below 10% as well (-0.77).
- KPI2: Regarding the survival rate, between 2001-2011, from an average of 16.40% for 2011-2021, it also decreases, to 14.29% (difference of -0.14).
- KPI3: The Average Crew Death Rate per Operator is 3%.
</center>

## Miscellany:
### Bar graph: 
<center>
The time when the most accidents occurred was 2:00 p.m. (with 620 deaths).
</center>

### Number of Deaths by Operator: 
<center>
Aeroflot with almost 5,000 deaths throughout the 113 years of air flights around the world.
</center>

### Box plot with whiskers ([Python notebook](https://github.com/melinnicri/Air_accidents/blob/main/Acc_aereos.ipynb)): 
<center>
Regarding the deceased Passengers, between 1908 and 2021, an average of 17 is shown, with a standard deviation of 33 (dispersion of the data), in 25% of the accidents there is 1 deceased passenger, in 50% there are 6 deceased passengers, in 75% there are 19 deceased passengers, there was a maximum of 560 passengers (and a minimum of 0 deceased passenger).

<p align="center"><img src="https://github.com/melinnicri/Air_accidents/blob/main/images/Pass_fatal.jpg"></p>


Regarding deceased crew members, between 1908 and 2021, there is an average of 6, standard deviation of 19, in 25% of accidents there is 1 deceased crew member, in 50% there are 3 deceased crew members, in 75% there are 5 deceased crew members, there was a maximum of 505 (minimum 0) deceased crew members.

<p align="center"><img src="https://github.com/melinnicri/Air_accidents/blob/main/images/Crew_fatal.jpg"></p>

Values outside the boxes would be outliers.
Among the values of the deceased crew members, less distance is seen in relation to the values of the deceased passengers (it could be due to the higher number of counts)(see [“eda.ipynb”](https://github.com/melinnicri/Air_accidents/blob/main/eda.ipynb)).
</center>

### END …_@v
