# Surf's Up! : a statistical analysis of temperature data from weather stations on Oahu
This report has been prepared for W. Avy by Bootcamp Data Analytics to consider for a proposed surf shop/ice cream shop on Oahu, Hawaii.

## Overview
Precipitation and temperature was obtained in a SQLite database for nine weather stations on Oahu.  Precipitation was studied from all stations over the period of one year.  For temperature, one weather station had more data than the others, so this was the focus of the statistical analysis of temperature.  It was thought that surfing conditions and ice cream consumption patterns would conincide when there was not much rain and the average temperature were right.  The temperature and precipition data are considered in more detail in Results.

## Resources 
Python 3.7.3, SqlAlchemy, Flask, Jupyter Notebook, SQLite

## Purpose
The purpose of this study is to contribute a data analysis towards making a sound financial and business decision on where to open a surf shop/ice cream shop on Oahu.

## Precipitation Results
Precipitation can be seen in this bar chart as daily precipitation in inches.  Accounting from data from all 9 weather stations, one can see that in a year's time there are only 5 days in which precipitation is greater than 3".
Daily Precipitation vs Date [https://github.com/CaroShaf/surfs_up/blob/main/Resources/precip.png]

The mean and 50% quartile are both near 2/10ths of an inch, with the max being 6.7 inches and the standard deviation being about 1/2 an inch.  The distribution is slightly skewed towards the right, making the assumption of short periods of light rain daily common.
Precipitation Central Tendencies [https://github.com/CaroShaf/surfs_up/blob/main/Resources/precipstats.png]

## Temperature Results
Temperature at weather station, USC00519281, revealed that the minimum temperature was 54 degrees, maximum 85 degrees, with an average of 71.66, over seven years of data.  This weather station was selected because it had the most temperature observations.  This was not the best reasoning, however.  The Waihee weather station at 21°27'06.0"N 157°50'56.0"W is approximately 2.5 miles inland from the Kaneohe Bay on the eastern side of Oahu.  The majority of key surfing spots are on the northern side of the island, with some on the south near Honolulu and few more on the western side of the island.  The temperature results are not extremely different at all weather stations, however, due to the area of Oahu, itself, being about half of the size of the state of Rhode Island.  When all temperature data is looked at across the nine weather stations, across the seven years of data, one sees that the average temperature is 73 degress with the most typical weather frequently occurring in the 74-77 degree range.

Temperature Histogram [https://github.com/CaroShaf/surfs_up/blob/main/Resources/temp-hist.png]
June Temperature [https://github.com/CaroShaf/surfs_up/blob/main/Resources/JuneTemps.png]
December Temperature [https://github.com/marketplace]


### Key difference in temperature between June and December
Although there are about 200 fewer temperature observations due to two weather stations that contributed no readings after 2015, the data is still statistically valid. 

  * Max temp - there is only a two degree difference between June's max temp (85) and December's max temp (83)
  * Min temp - there is around 8 degrees difference between June's min temp (64) and December's min temp (56)
  * Mean temp - there is only a 4 degree difference between June's mean temp (75) and December's mean temp (71)

## Summary


### Additional queries to gather more weather data
* Wind data is critical!  Waves are a product of wind.  Seasonal average wind speed and direction at the various weather stations is more important than temperature.  
* It would also be important to understand whether or not the minimum temperatures were based on the daily lows and if all temperature observations were taken at the the same
* time day.

### Additional business data to gather
* Surfer business patterns - what audience/level of surfers are interested in ice cream?  Professional surfers are very health conscious. 
* Ice cream popularity in HI data - tourists may be more interested in local traditions such as shave ice, and it is a healthier option for professional level surfers.
* Review of successful surf shops/ice cream shops globally - Australia is well known for some of its surfing beaches.  Of course, Hawaii is too, but not all beaches of the island equally.  So successful businesses may already have prime locations for such a proposed business.  But Lake Michigan may be an untapped market!  Hardcore surfers flock to locations in Wisconsin, Michigan and Illinois from September through April to catch great waves, demonstrating that temperature is not the most critical factor in surfing.  Ice cream would not be a hot item (literally) to sell to these surfers.
