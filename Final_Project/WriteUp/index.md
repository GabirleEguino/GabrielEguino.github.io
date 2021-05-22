Introduction:

This past Spring, 2021 semester, I had the opportunity to live in Baltimore. Throughout my semester here, I didn’t have a car to move around the city and was constrained to the eastern part of the city to do my grocery shopping. As I walked around my neighborhood, I noticed that there were very few large grocery stores nearby. There were a few bodegas around, but most of them had a limited selection and overcharged for essential goods. I had to walk approximately a kilometer to get to the nearest large grocery store every weekend to do most of my grocery shopping. 

My experience living here led me to think about how Hispanic people throughout Baltimore struggle accessing healthy food at a good price and acceptable distance. I wanted to find out what type of markets were available for densely populated Hispanic census tracts, how far of a distance it would be for someone who could not afford a car to walk to get groceries from a large supermarket, and the change from 2014 to 2019’s accessibility to see if there has been a gradual improvement or not. 

Data:

For this project, I acquired my data related to total population, Hispanic population, and median household income from the U.S Census Bureau. I collected data on market types and their locations through Bmore Open Data. Using R Studio, I created a variable that calculated the population density of Hispanic people per census tract. This data was then exported into QGIS where I specified break points based on three classes to create my bivariate map. 

Hispanic population density: 0-15%, 15-30%, and 30-55%

Median household income: 0-$50,000, 50,000-$100,000, and 100,000- $200,000

Mapping:

In order to create both maps, I used QGIS. QGIS allowed me to geocode the .csv I gathered from Bmore Open Data that contained the type of markets and their locations. I had to add fields such as city, state, and country, in order to help make the geocoding process more accurate. Along with the geocoded points, I followed a guide provided by our professor called “Bivariate choropleth maps: a how-to guide” to multiply both the Hispanic population density, with each their own respective graduated symbology, and the median household income. I additionally added a 1km buffer to the large supermarket locations to pinpoint how many census tracts would be accessible for people to potentially walk to get groceries.

Conclusion:

In conclusion, I found that in areas where there is at least a 30% Hispanic population density, in both 2014 and 2019, there was only one large supermarket accessible for this group of people within a 1km radius. Interestingly enough, as the Hispanic population density shifted more towards Eastern Baltimore and their median household increased relatively from 2014, they were still constrained to only one large supermarket. In comparison, areas in Northern Baltimore had a census tract that had two large supermarkets for the same level of median household income. This disparity goes to show that there still has to be a lot done for the Hispanic population in Baltimore. Their population density in Eastern Baltimore has been increasing since 2014 and in order to provide these people equal access to healthier, cheaper, and accessible food, there must be more large supermarkets placed in these areas.

References:

American Community Survey Tables: 2015 -- 2019 (5-Year Estimates) (2270 tables) - American Community Survey Tables: 2015 -- 2019 (5-Year Estimates) (ACS19_5yr) - ACS 2019 (5-Year Estimates). Social Explorer. (n.d.). https://www.socialexplorer.com/data/ACS2019_5yr/metadata/?ds=ACS19_5yr.
Baltimore Open Data. (n.d.). https://data.baltimorecity.gov/. 
Bivariate Choropleth Maps: A How-to Guide. Joshua Stevens - Visual Communicator. (n.d.). https://www.joshuastevens.net/cartography/make-a-bivariate-choropleth-map/. 
