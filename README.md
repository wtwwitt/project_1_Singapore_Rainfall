# Executive Summary

When traveling to Singapore, it seems that visitor will likely to encounter rain whatever the month is. This data analysis project aimed to explore and understand the patterns and characteristics of rain in Singapore.

By using various datasets, finding relationship between each datasets and visualizing the data, the result should be able to help those who plan to travel to Singapore to get better preparation and adaptation on their plan for the good traveling experience.

|Feature|Type|Dataset|Description|
|---|---|---|---|
|month|datetime|rain_df|Month (YYYY-MM-01)|
|rain_days|integer|rain_df|Monthly number of rainy days|
|rain_amount|float|rain_df|Amount of monthly rainfall, in mm(millimeters)|
|humidity|float|rain_df|Monthly average relative humidity|
|sun_hrs|float|rain_df|Monthly average sunshine hours|
|mean_temp|float|rain_df|Monthly average surface temperature (degree celsius)|
|date|datetime|Flight Price|Date (DD-MMM)|
|price|datetime|Flight Price|Average flight price from Bangkok to Singapore (round-trip, 4 days) in baht|

The analysis is mainly focus on the number of rainy days and rain amount, as it will be the most concerned factors for travelers.

### **From EDA and Visualization, it has been found that**
* In 1990, 2000, 2010 and 2020, December has the highest number of rainy days and rain amount while January has the lowest.

* 2007 has the highest amount of total rainfall and the lowest is in 1997.

* 2013 has the highest number of rainy days while lowest is also in 1997.

* There is no trend in the number of rainy days and the amount of rain over the past years (stay the same over the past years).

![No Trends in Rainy Days](images/no_trend.png)

* Number of rainy days, total rain amount, humidity and number of sunshine hours are related at a moderate level.

![Correlation Heatmap](images/corr_heatmap.png)

* From the data, splitted into peak, regular, and lowest rainfall month, the average number of rainy days are
    * Nov, Dec (peak): 19 (with 99% chance of 9 rain days or more)
    * Jan and Mar-Oct (rugular): 14 (with 99% chance of 5 rain days or more)
    * Feb (lowest): 8

![Minimum Rainy Days Chance](images/rain_chance_nov_dec.png)

* In average, December have the highest total amount of rain over the past years and February has the lowest.
    
* If the average sunshine hours is higher than 6.5 or lower than 4.5 hrs. the number of rainy days in that month goes up or down significantly.

![Rainfall and Sunshine Hours](images/Comparison%20of%20Rainfall%20and%20Sunshine%20Hours.png)

### In summary

Considered the number of rainy days, the best month to travel to Singapore is February with relatively low temperature.
However, it can be crowded as Chinese New Year usually falls in February, picking the period earlier of later in the month should be better.

![Crowded Months](images/crowded_month.png)

Avoid November and December as they are the wettest months with additional of relatively high flight price.

![Flight Price](images/flight_price.png) 

Also, in November and December, if it still haven't rain at least 9 days at the near end of the month, keep it mind that it is likely to rain every day from that point.

If there is no choice but to go to Singapore in November or December, focuses more or always prepare for an indoor alternate plan so you can switch anytime.

For the other months (January and March to October), the weather condition should likely be the same. If you don't expect to go there in the "Greate Singapore Sale" season, it's better to avoid June and July. In this period, the most recommended month for sighseeing and outdoor activities are March and April.