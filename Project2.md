## Lima, Peru Population Mapping

# Population Count Histogram

The image below is a histogram showing population totals within the 2nd administrative level for the Lima region.

![alt text](per_adm2_histogram.png)

# Population Density Graph

A line plot describing population density within Lima's 2nd administrative level is shown below.

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/per_adm2_density.png)

# Population Density Histogram and Line plot

The population density histogram for Lima's 2nd administrative level is shown below. The line plot and histogram do not follow the same distribution. A possible explanation is that the log function should've been used to scale down the data.

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/per_density_histogram.png)

# Night Time Lights Regression

The image below is a regression showing the relationship between population within Lima's 2nd administrative level and night time lights data.

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/per_pop20_ntl_regression.png)

# Four Variable Regression

The image below shows the relationship between population, and all of the land cover land use data (water, night time lights, land cover, land use).

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/per_regression_4_variables.png)

# Lima Population Plot

The image below shows population distribution throughout Lima on a plot. Something went wrong here as population should not be uniformly distributed throughout the region. This plot uses 2015 worldpop data, and a 2020 worldpop data plot is included below for comparison.

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/lima%20population.png)

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/Lima%20Population.png)

# Population differential

The image below is supposed to show the difference between the predicted and actual population of the Lima rergion using 2015 worldpop values. Whatever error that made the population plot show a uniform distribution, carried over to this plot as the real vs predicted population difference is the same for all of Lima.

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/limadiff.png)

# 3D Population Model

The 3D population model shows variation throughout the Lima region, with a concentration of population along the northern coast.

![alt text](https://github.com/bobbybWM/Workshop-1/blob/master/lima3D.PNG)

# Conclusion

Some sort of error with the population plot needs to be corrrected. I played around with the the stat function to see if that helped, but could not make it work. Additionally the combination line plot/histogram needs to be adjusted with the log scale. Outside of these errors, I was able to learn that the land use, land cover, night time lights, and water raster data are correlated to the actual distribution of population in Lima's second administrative region (the regressions prove this). 
