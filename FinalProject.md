# Final Project: An Examination of Human Development in Peru

## Political Subdivisions

Peru has 3 administrative divisions. Because of the large size of Peru, my analysis was limited largely to the 2nd and 3rd administrative divisions, as my computer could not process the roughly 330 million gridcells required to look at Peru as a whole. Because of this my analysis mostly centered around the Lima region of Peru, while later zooming in on Huancabamba, Peru. Pictured below is a map showing Peru's 1st and 2nd administrative divisions.

![alt text](my_LMIC20(1).png)

## Lima Region Population

![alt text](LIMA.png)

The above images show population density throughout the Lima region. The Lima region of Peru includes Peru's capital (also named Lima), and is located in Western Peru, on the Pacific coast. As the map and accompanying chart show, Lima's most densely populous districts are Cañete, Huaura, and Huaral. This makes sense as those districts are all on Peru's Pacific coast, and therefore have port access. The access to industry presumably explains the heavy population centers. The interior districts of the Lima region have less densely populated areas which may be explained by their lack of port access, and/or their status as suburban areas.

Below, a histogram showing Lima's population centers is displayed. The variance in population count shown by the histogram suggests that the different regions of Lima did not develop uniformly. There are many possible explanations for this such as some areas being zoned for commerce rather than residence, wealthier people wanting and paying for more land, driving down the population count in some suburban areas, and a myriad of other reasons.

![alt text](per_adm2_histogram.png)

Pictured below is a four variable regression showing the Lima region's population and land cover/land use data. The land cover land use data includes topography, water, vegetation, and nighttime lights data. The model fits the actual population nicely, with an r squared value of .8831, suggesting that the land use/land cover data are accurate predictors of population. The points below the line suggest that their populations are slightly lower than the land use/land cover data would indicate, and the points above the line have slightly higher populations than the four variables would predict.

![alt text](per_regression_4_variables.png)

## Access to Healthcare and Roadways in Huancabamba, Peru

Huancabamba, Peru is located in the Northeast corner of the country, near the Ecuadorean border. Huancabamba was chosen for its population count (about 124,800), making the computations manageable in terms of grid cells.  

![alt text](healthcare_access_huancabamba.png)

The blue lines represent driveable roadways throughout Huancabamba. The red dots are doctors offices and the black dots are clinics. There was no distinction between the capabilities of the clinics and offices in the HDX data, and the only thing I could determine through further reasearch was that the healthcare facilities are all state run. Interestingly, Peru does have a National Bureau of Statistics, but it seems to focuse more on economic statistics than anything else, so a lack of data at the country level could be to blame for this. As you can see many healthcare facilities are not situated near the roadways or population centers. A possible explanation for this is that the mountainous topography prevented development in several areas, as well as necessitated the need for doctors in small, mountainous villages.

![alt text](2994.png)

Shown above is a 3D rendering of Huancabamba, Peru. Some notable takeaways are that the region is very mountainous, urban centers, aer largely contained to the valleys, and roadways do not offer a large degree of interconnectivity throughout the region, as they are largely limited to the central part of the region. This helps explain the findings provided by the 2D plot that topography has limited the placement of healthcare facilities near driveable roadways and population centers.
