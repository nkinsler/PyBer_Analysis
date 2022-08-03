# PyBer_Analysis

## Resources
- Data Source: [city_data.csv](https://github.com/nkinsler/PyBer_Analysis/blob/main/Resources/city_data.csv)
- Data Source: [ride_data.csv](https://github.com/nkinsler/PyBer_Analysis/blob/main/Resources/ride_data.csv)
- Software: Python 3.7 (64 bit)
- Python: [PyBer_Challenge](https://github.com/nkinsler/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Overview of the Analysis

V. Isualize has requested that a summary DataFrame of the ride-sharing date by city type using Python and knowledge of Pandas.  A multiple-line graph was requested that displays total weekly fares for each city type utilizing Pandas and Matplotlib.

Summary DataFrame to show total rides, total drivers, total fares, average fare per ride, and average fare per driver by city type (rural, suburban, and urban).

Mulitple-line graph to display total fares by week for the period of January 1, 2019 to April 28, 2019 for each city type.

## Results

### Ride-Sharing Summary DataFrame by City Type
![PyBer_Summary](https://github.com/nkinsler/PyBer_Analysis/blob/main/Analysis/PyBer_Summary.png)!

Rural city types experience significantly fewer rides and have fewer drivers.  Rural city types average fare per ride is roughly $4 more than suburban and roughly $10 more than urban.  Rural city types average fare per driver is roughly $15 more than suburban and $38 more than urban.

In contrast, urban city types have a significantly higher total ride count and significantly more drivers.  Average fare per ride and average fare per driver is the lowest of the three city types.

### Multiple-Line Chart of Total Fares for Each City Type
![PyBer_fare_summary](https://github.com/nkinsler/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)!

Urban city types lead the three city types by total fares for each week in 2019 from January through April.  Urban has a steady increase in total fares throughout the period with 4 weeks’ worth investigating further (February week 3, March week 2, 3, and 4).

Suburban city types tend to hover around weekly fares $1,000 with a spike during the 3rd week of February and 4th week of April.  Rural city types tend to hover around weekly fares of $250 with spikes the 3rd week of February and 4th week of March.  Given the consistency of the total fares each week, these may recurring ride shares.

The 3rd week of February saw total fares increase across all three city types.  This may suggest a high demand period.

## Summary and Recommendations

1. Given that urban city type has the highest number of rides and drivers, I would recommend the study of surge pricing.  Timing of surge pricing would have to be further researched, but should focus around holidays, weekends, and major events to maximize the fare during high demand times.  Surge price could lead to an overall increase to average fares per ride and driver.
2. Rural city type has the fewest total rides and total drivers, but the highest average date per ride and driver.  Given the low number of fares received, I would recommend either ending service to rural city types or a reduction of service.  Rural city types would have a highly reduced demand for ride sharing given the increased proximity to other locations when compared to urban and suburban areas.
3. Given the steady total fares by week in the suburban and rural area, I would recommend a research study into the potential of offering carpooling ride share option for those two city types.  Car pool option would reduce the number of drivers needed and would potentially increase the average fare per ride by including multiple riders with only a slightly reduced fare per rider.
