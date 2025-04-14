# AnalyzingWildfireAustralia

In this project, we have analyzed Wildfire activities in Australia

We have used libraries such as Matplotlib, Pandas, Seaborn and Folium to create informative plots and charts:
pandas for managing the data.
numpy for mathematical operations.
seaborn for visualizing the data.
matplotlib for additional plotting tools.

Dataset
Historical Wildfires

This wildfire dataset contains data on fire activities in Australia starting from 2005. Additional information can be found here.

Variables

1) Region: the 7 regions
2) Date: in UTC and provide the data for 24 hours ahead
3) Estimated_fire_area: daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% for a each region in km2
4) Mean_estimated_fire_brightness: daily mean (by flagged fire pixels(=count)) of estimated fire brightness for presumed vegetation fires with a confidence level > 75% in Kelvin
5) Mean_estimated_fire_radiative_power: daily mean of estimated radiative power for presumed vegetation fires with a confidence level > 75% for a given region in megawatts
6) Mean_confidence: daily mean of confidence for presumed vegetation fires with a confidence level > 75%
7) Std_confidence: standard deviation of estimated fire radiative power in megawatts
8) Var_confidence: Variance of estimated fire radiative power in megawatts
9) Count: daily numbers of pixels for presumed vegetation fires with a confidence level of larger than 75% for a given region
10) Replaced: Indicates with an Y whether the data has been replaced with standard quality data when they are available (usually with a 2-3 month lag). Replaced data has a slightly higher quality in terms of locations
